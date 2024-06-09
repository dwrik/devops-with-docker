# base image
FROM golang:1.21-alpine

# expose port
EXPOSE 8080

# change project directory
WORKDIR /usr/src/app

# copy src code
COPY . .

# set env variables
ENV REQUEST_ORIGIN=http://localhost:3000

# build code
RUN go build

# run
ENTRYPOINT ["./server"]
