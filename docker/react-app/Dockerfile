FROM node:latest

RUN apt-get update && \
    apt-get install -y git

ENV APP_PATH=/react-app
RUN mkdir $APP_PATH
WORKDIR $APP_PATH

RUN npx create-react-app .