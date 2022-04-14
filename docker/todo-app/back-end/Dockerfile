FROM node:14-alpine
WORKDIR /app
ADD /node_modules.tar.gz ./
COPY package.json ./
RUN npm install
EXPOSE 3001
CMD npm start
