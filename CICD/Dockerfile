FROM node:22-apline

WORKDIR /app

copy . .
RUN npm ci


EXPOSE 3000

CMD ["npm", "start"]