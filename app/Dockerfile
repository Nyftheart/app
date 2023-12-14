FROM node:14

WORKDIR /Users/nyftheart/Documents/hello-world-project-master/hello-world-project-master

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]
