FROM node:7
WORKDIR /newapp
COPY package.json /newapp
RUN npm install
COPY . /newapp
CMD node server.js
EXPOSE 3000