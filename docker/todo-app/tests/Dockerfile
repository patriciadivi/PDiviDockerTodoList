FROM node:14-alpine

WORKDIR /Tests

EXPOSE 3001

ADD node_modules.tar.gz .

COPY . ./Tests

CMD ["npm", "start"]

