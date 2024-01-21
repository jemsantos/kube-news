# docker build -t jemsantos/kube-news:v1 -f Dockerfile .
# FROM node:18.19.0 minha versao
FROM node:20.5.1
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
# porta definida no server.js
EXPOSE 8080
CMD ["node", "server.js"]
