FROM node:14.17.5
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 1342
CMD ["node", "server.js"]
