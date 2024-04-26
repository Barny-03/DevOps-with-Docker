FROM node:16.20.2

WORKDIR /app

COPY . .

RUN npm install

RUN npm run build

RUN npm install -g serve

EXPOSE 5000

ENV REACT_APP_BACKEND_URL=http://192.168.3.18:8080

RUN npm run build

CMD ["serve", "-s", "-l", "5000", "build"]