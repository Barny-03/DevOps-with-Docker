FROM node

WORKDIR /app

RUN apt install -y git

RUN git clone -b master --single-branch https://github.com/Barny-NX/project.git

RUN npm install

CMD ["node","app.js"]