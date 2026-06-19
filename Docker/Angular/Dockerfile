FROM node:24.16.0-alpine
WORKDIR /usr/src/app

RUN npm install -g @angular/cli

COPY package*.json ./
RUN npm install

COPY . .

CMD ["ng", "serve", "--host", "0.0.0.0"]