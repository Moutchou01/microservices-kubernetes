FROM node:8-alpine


WORKDIR /usr/src/app

COPY package.json ./
RUN npm install

COPY . .
EXPOSE 8082

CMD ["sh", "-c", "npm start" ]
