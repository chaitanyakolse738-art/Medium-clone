FROM node:24-alpine

WORKDIR /medium-clone

COPY package*.json ./

RUN npm ci

COPY . .

EXPOSE 8000

CMD ["npm", "run", "dev"]
