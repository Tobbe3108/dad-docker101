### Kør en container:

docker run <image-navn>

### Kør en container og mappe en port:

docker run -p <værtsport>:<containerport> <image-navn>

### Kør en container i baggrunden:

docker run -d <image-navn>

### Se alle kørende containere:

docker ps

### Se alle containere (også de inaktive):

docker ps -a

### Stop en container:

docker stop <container-id>

### Fjern en container:

docker rm <container-id>

### Fjern alle containere:

docker rm $(docker ps -aq)

### Byg en Docker-image:

docker build -t <image-navn> .

### Push en Docker-image til Docker Hub:

docker push <image-navn>

### Træk en Docker-image fra Docker Hub:

docker pull <image-navn>

### Se Docker logs for en container:

docker logs <container-id>

### Kør en kommando inde i en container:

docker exec <container-id> <kommando>

### Se detaljeret information om en container:

docker inspect <container-id>

### Se detaljeret information om en image:

docker image inspect <image-navn>