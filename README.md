# Docker and Docker-Compose on Cloud9
Cloud9 can be used to test your code using docker containers. 

Using Docker-Compose you are able to bring up a Development environment of a Microservices Application Stack.

## Interesting links 
- https://aws.amazon.com/blogs/publicsector/how-to-develop-microservices-using-aws-cloud9-docker-and-docker-compose/
- https://github.com/star3am/tmpstuff
- https://www.ecloudture.com/en/getting-started-with-docker-container-in-aws-cloud9/
- https://www.cloudbees.com/blog/using-docker-compose-for-nodejs-development

### Instructions
- Clone this repo onto your Cloud9 environment
- Copy docker-compose binary to ~/bin `cp bin/docker-compose ~/bin/`
- Check Docker and Docker-Compose versions with `docker -v` and `docker-compose -v`
- Run the app, by doing `cd app && docker-compose up`
- Check your app in Cloud9

#### Gotchas
- Cloud9 only worked for me on port 8080 see: docker-compose.yml
- Docker-Compose was not present on Cloud9 instance and I was unable to install it due to Firewall restrictions hence why I bundled it with this code.
