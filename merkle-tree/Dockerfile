FROM node:18.19

WORKDIR /app

COPY ./config ./config
COPY ./package.json ./
COPY ./src ./src
COPY ./test ./test
COPY ./.babelrc ./
RUN npm i

CMD npm start
