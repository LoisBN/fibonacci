FROM node:alpine

WORKDIR /app/worker

COPY ./package.json ./
RUN yarn
COPY . .

CMD [ "yarn","start" ]