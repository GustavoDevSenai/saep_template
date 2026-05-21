FROM node:20-alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

# O Next.js roda por padrão na porta 3000
EXPOSE 3000

CMD ["npm", "run", "dev"]