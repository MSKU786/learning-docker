# Specify base image
From node:alpine

# this will store all the app file iniside this directory in the container
WORKDIR /usr/app

# INstall dependenices
COPY ./ ./
RUN npm install

CMD ["npm", "start"]