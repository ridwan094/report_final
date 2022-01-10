FROM node:14-alpine
WORKDIR /usr/src/app
RUN npm install
RUN npm install --save-dev sequelize-cli -g
EXPOSE 5000
CMD [ "npm", "start" ]
