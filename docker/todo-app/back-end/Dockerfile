FROM node:14-alpine

WORKDIR /Back-End

EXPOSE 3001

ADD node_modules.tar.gz .

COPY . ./Back-End

CMD ["npm", "start"]
