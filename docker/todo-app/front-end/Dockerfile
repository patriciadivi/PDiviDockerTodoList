FROM node:14-alpine

WORKDIR /Front-End

EXPOSE 3000

ADD node_modules.tar.gz .

COPY . ./Front-End

CMD ["npm", "start"]
