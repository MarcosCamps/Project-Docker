FROM mjgargani/puppeteer:trybe1.0
WORKDIR /tests
ADD node_modules.tar.gz .
COPY . ./tests
CMD ["npm", "test"]
