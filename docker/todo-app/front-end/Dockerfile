FROM node:14-alpine

WORKDIR /user

EXPOSE 3000

ADD node_modules.tar.gz ./

COPY . .

CMD [ "npm", "start" ]