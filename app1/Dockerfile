FROM node:14

WORKDIR /app1

COPY package.json .
COPY package-lock.json .

RUN npm install

COPY index.js .

EXPOSE 4000

CMD [ "node", "index.js" ]