# pacman-docker
Pacman Game - Docker App (2024)



## Download the code and Build the container
```bash
git clone https://github.com/Juli-BCN/pacman.git
cd pacman
docker build -t pacman .
docker images
```


## Run, Test & Stop the Docker container
```bash
docker container run --rm -d -p 80:80 pacman
curl -L http://localhost
docker ps
```

> :eyeglasses: docker container stop *CONTAINER_ID*