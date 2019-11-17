FROM node:latest

WORKDIR /home/node/app
COPY /app /home/node/app 

RUN npm update && npm install
ENV NODE_ENV=production

EXPOSE 5000

CMD [ "npm start" ]
