FROM node:16

WORKDIR /usr/src/app

COPY package*.json ./

ENV REACT_APP_BACKEND_URL=http://localhost:8080

RUN npm install

COPY . .

RUN npm run build

EXPOSE 5000

CMD ["npx","serve", "-s", "-l", "5000", "build"]

