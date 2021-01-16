FROM node:14-alpine3.12
COPY package*.json .
RUN npm i  
COPY server.js .
CMD ["npm","start"]