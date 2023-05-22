FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USER=mike
ENV MONGODB_PASS=secret

CMD [ "npm", "start" ]
