FROM node:alpine
WORKDIR '/app'
#Install dependencies
COPY package.json ./
RUN npm install
COPY ./ ./
CMD ["npm","run","start"]

