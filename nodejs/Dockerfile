FROM node:14-buster-slim

WORKDIR / 

COPY package.json .
RUN npm install
RUN npm install -g nodemon
COPY . .

EXPOSE 3000
CMD [ "npm", "start" ]
