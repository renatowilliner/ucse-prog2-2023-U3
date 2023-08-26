FROM node:14

WORKDIR /app2

COPY package.json .
COPY package-lock.json .

RUN npm install

COPY index.js .

EXPOSE 4001

CMD [ "node", "index.js" ]
