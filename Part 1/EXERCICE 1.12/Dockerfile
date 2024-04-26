FROM node:16.20.2

EXPOSE 5000

WORKDIR /app

COPY . .

RUN npm install

RUN npm run build


CMD ["serve", "-s", "-l", "5000", "build"]