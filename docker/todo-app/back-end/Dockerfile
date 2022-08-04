FROM node:alpine

WORKDIR /todo-app/back-end

COPY . .

ADD node_modules.tar.gz .

RUN npm install

EXPOSE 3001

CMD [ "npm", "start" ]