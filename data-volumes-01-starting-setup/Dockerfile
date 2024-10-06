FROM node:14

WORKDIR /app
# we can do COPY package.json /app as well but we don;t have to do that as we already have set working directory to /app
COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

CMD ["node", "server.js"]