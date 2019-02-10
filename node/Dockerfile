FROM node:latest

RUN mkdir -p /usr/src/app

WORKDIR /usr/src/app

COPY ./code/package.json /usr/src/app/

RUN npm install

COPY ./code /usr/src/app

CMD ["npm", "start"]
