FROM mjgargani/puppeteer:trybe1.0
WORKDIR /tests
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . /tests
ENTRYPOINT ["npm", "test"]