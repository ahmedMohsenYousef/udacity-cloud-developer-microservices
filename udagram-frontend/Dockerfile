FROM node:11

WORKDIR /www/app

COPY . /www/app

RUN npm install -g cordova ionic

RUN npm install

EXPOSE 8100

CMD ["ionic", "serve","--external","--address"]