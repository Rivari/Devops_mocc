FROM node:10-jessie

WORKDIR /usr/scr/app
COPY /backend ./

RUN npm install
ENV NODE_ENV=production
#ENV REDIS=localhost

EXPOSE 8000