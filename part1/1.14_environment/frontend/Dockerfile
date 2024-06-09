# base image
FROM ubuntu:22.04

# expose port
EXPOSE 5000

# change project directory
WORKDIR /usr/src/app

# setup nodejs
RUN apt-get update
RUN apt-get install -y curl
RUN curl -sL https://deb.nodesource.com/setup_16.x | bash
RUN apt-get install -y nodejs

# setup project & dependencies
COPY package* .
RUN npm install

# copy src code
COPY . .

# set env variables
ENV REACT_APP_BACKEND_URL=http://localhost:8080

# build code
RUN npm run build
RUN npm install -g serve

# run
ENTRYPOINT ["serve", "-s", "-l", "5000", "build"]
