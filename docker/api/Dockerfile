FROM node:10

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

COPY package*.json /usr/src/app
COPY index.js /usr/src/app

RUN npm install -g nodemon

RUN npm install

COPY . /usr/src/app

ENTRYPOINT [ "node", "--inspect=0.0.0.0","index.js"]

EXPOSE 3000

CMD ["npm","start"]