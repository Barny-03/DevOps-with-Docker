FROM node:16.20.2

EXPOSE 5000

WORKDIR /app

COPY . .

RUN npm install

RUN npm run build

RUN npm install -g serve

ENV REACT_APP_BACKEND_URL=http://localhost:8080

CMD ["serve", "-s", "-l", "5000", "build"]