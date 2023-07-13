FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV MONGODB_USERNAME=root
ENV MONGODB_PASSWORD=1234

EXPOSE 80

CMD [ "npm", "start" ]