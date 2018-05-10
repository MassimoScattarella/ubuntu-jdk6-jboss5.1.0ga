# DOCKER ubuntu-jdk6-jboss5.1.0ga
## Build

    docker build -t ubuntu-jdk6-jboss5.1.0ga .
   
## Run
    docker run \
     -p 8009:8009 \
     -p 8080:8080 \
     -d --rm \
     maxtacs/ubuntu-jdk6-jboss5.1.0ga 
