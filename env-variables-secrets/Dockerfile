FROM node:16

ENV MONGODB_CONNECTION_PROTOCOL mongodb+srv
ENV MONGODB_DB_NAME gha-demo
ENV MONGODB_CLUSTER_ADDRESS cluster0.sizxk9i.mongodb.net
ENV MONGODB_USERNAME
ENV MONGODB_PASSWORD

WORKDIR /app

COPY package*.json .

RUN npm install

COPY . .

CMD ["npm", "start"]