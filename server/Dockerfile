FROM node:alpine

WORKDIR /server

ADD . /server

RUN npm install
RUN npm install nodemon -g
RUN npm run compile

CMD ["npm", "run", "dev"]

EXPOSE 5555