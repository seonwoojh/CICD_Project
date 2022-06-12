FROM node:14-slim

WORKDIR / 

COPY package.json .
RUN npm install
RUN npm install -g nodemon
COPY . .

EXPOSE 3000
CMD [ "npm", "start" ]
