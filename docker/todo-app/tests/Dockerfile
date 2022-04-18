FROM mjgargani/puppeteer:trybe1.0 As todotests
WORKDIR /app
COPY . .
ADD node_modules.tar.gz ./
EXPOSE 3000
ENTRYPOINT [ "npm", "test" ]