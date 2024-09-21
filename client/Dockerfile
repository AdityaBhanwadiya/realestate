FROM node:14

WORKDIR /app

COPY package*.json ./

RUN cd client && \
    npm install && \
COPY . .

RUN npm run build