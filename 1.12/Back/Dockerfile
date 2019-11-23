FROM node:10-jessie

WORKDIR /usr/node/server
COPY /backend /usr/node/server

RUN npm update && npm install
ENV NODE_ENV=production

EXPOSE 8000

CMD [ "npm start" ]


