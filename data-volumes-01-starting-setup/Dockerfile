FROM node:14

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

# default port
ENV PORT 80

EXPOSE $PORT

CMD ["npm", "start"]