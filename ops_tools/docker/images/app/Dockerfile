FROM node:10-alpine

WORKDIR /app
COPY ./package*.json ./
RUN npm install

EXPOSE 8080
CMD [ "npm", "run", "start:dev" ]

