FROM node:alpine

WORKDIR /todo-app/front-end

COPY . .

ADD node_modules.tar.gz .

RUN npm install

EXPOSE 3000

CMD [ "npm", "start" ]