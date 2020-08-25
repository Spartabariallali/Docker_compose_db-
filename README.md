### What is Docker?
- open source software for containerisation - developing, shipping and running applications

- What is the difference between VM and Docker containerisation
- VM emulate a OS and therefore are resource intensive while containerisation shares the machines resources making it super light weight.

### What are the benefits of Docker?
- Consist delivery of your application
- light weight
- open-source
- Can be scaled up significantly using Kubernetes


### Docker client - localhost
- Host machine --> API calls --> Docker Daemon --> Docker Hub

                  Docker pull

                  Docker Build

                  Docker run


Docker looks for containers on the local host first and if they are not available makes an API call that connects with the Docker Daemon. If the image does not exist within the docker daemon it goes to the docker hub and returns the image to the local host

  
