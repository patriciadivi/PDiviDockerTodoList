FROM mjgargani/puppeteer:trybe1.0

WORKDIR /Tests

ADD node_modules.tar.gz .

COPY . ./Tests

CMD ["npm", "test"]

