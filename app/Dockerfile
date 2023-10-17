#FROM node:18
FROM rafaelcambito/node18rafael2
WORKDIR /usr/src/app
RUN npm install express mysql
COPY ./server.js ./server.js
EXPOSE 3000 
CMD ["node", "server.js"]