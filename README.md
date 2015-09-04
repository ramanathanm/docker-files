# docker-files

* docker build --rm=true -t '<Image Name>'
* docker run --privileged=true -d -p 50022:22  -p 50080:80 -v /Users/ramanathanm/docker-mount:/home/build/host-mount --name=<Container Name> <Image Name>
* docker start <Container Name>
* docker stop <Container Name>
