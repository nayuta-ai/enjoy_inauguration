FROM node:latest

RUN apt-get update && \
    apt-get install -y git
    
ENV APP_PATH=/express-app
RUN mkdir $APP_PATH
WORKDIR $APP_PATH

RUN npm init -y
RUN npm install -y express cors pug jquery
