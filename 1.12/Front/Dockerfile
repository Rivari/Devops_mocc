FROM node:latest

WORKDIR /home/node/app
COPY /app /home/node/app 

RUN npm update && npm install
ENV NODE_ENV=production
ENV API_URL=http://localhost:8080 npm start

EXPOSE 5000

CMD [ "npm start" ]
