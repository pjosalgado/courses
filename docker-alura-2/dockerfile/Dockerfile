FROM node:25.6.0-bookworm

COPY . /var/www
WORKDIR /var/www

RUN npm install
ENTRYPOINT npm start
EXPOSE 3000
