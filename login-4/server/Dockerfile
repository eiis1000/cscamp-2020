FROM node:14
WORKDIR /usr/src/app

COPY package.json ./
COPY yarn.lock ./
RUN yarn install

COPY . .

EXPOSE 1337

CMD [ "yarn", "start" ]