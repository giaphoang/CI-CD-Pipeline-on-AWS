FROM node:14
WORKDIR /usr/app
COPY package.json .
RUN npm install
COPY . .
EXPOSE 9000
CMD ["node", "app.js"]