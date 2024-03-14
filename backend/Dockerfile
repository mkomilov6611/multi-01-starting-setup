FROM node:14

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8000

# default values for mongodb creds
ENV MONGODB_USERNAME root
ENV MONGODB_PASSWORD secret

CMD ["npm", "start"]