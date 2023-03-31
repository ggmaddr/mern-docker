FROM node:14

WORKDIR /app

COPY package.json .

RUN npm i

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME ggmaddr
ENV MONGODB_PASSWORD passgg

CMD ["npm", "start"]