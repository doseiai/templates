FROM node:20.12.2-slim

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
COPY package*.json ./

RUN npm install

COPY . ./

CMD ["node", "index.js"]
