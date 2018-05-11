FROM node:8.11.1

ENV HOME=/home/app/

COPY package.json yarn.lock $HOME

WORKDIR $HOME

RUN yarn

