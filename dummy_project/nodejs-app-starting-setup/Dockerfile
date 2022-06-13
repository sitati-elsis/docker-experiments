# base image
FROM node


WORKDIR /app

# this is optimisation
COPY package.json /app

# this command is usually executed in the working directory
RUN npm install

COPY . /app


# optional. Only for documentation
EXPOSE 80

# should always be the last instruction
CMD ["node", "server.js"]