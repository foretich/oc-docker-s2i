# simple dockerfile to test OCP s2i using Dockerfile 

FROM registry.access.redhat.com/ubi7:latest

# changed the following line by adding a hash at the front
# CMD ["/bin/bash", "-c", "sleep infinity"]
# changed the following line by removing the hash at the front
CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]
