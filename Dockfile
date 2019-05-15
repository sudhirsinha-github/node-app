FROM node:carbon
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY src /app
EXPOSE 80
CMD [ "node", "index.js" ]
