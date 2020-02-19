FROM node:alpine

WORKDIR /app/api

COPY ./package.json ./
RUN yarn
COPY . .

CMD [ "yarn","start" ]  