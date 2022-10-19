FROM node:latest
LABEL maintainer="GleisonFreire"
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
