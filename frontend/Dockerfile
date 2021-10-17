FROM node:16.3.0
WORKDIR /src
COPY package.json ./
RUN npm install
COPY . .
CMD ["npm", "start"]