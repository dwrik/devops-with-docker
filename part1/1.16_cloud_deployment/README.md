# 1.16 Cloud Deployment

## Description

- Used [render](https://render.com/) for deployment
- Chose **web service** as deployment type and selected the **from registry** option
- Created a separate tagged build for `linux-amd64` architecture using `--platform` flag since render requires `linux-amd64` type images
- Provided a link to the specific docker hub image of the app in render
- Customized app name, environment variables and other parameters
- Deployed it

## Links

- [App Link](https://hello-world-spring.onrender.com/)
- [Docker Hub Link](https://hub.docker.com/r/dwrik/hello-world-spring)
