# pacman-docker
Pacman Game - Docker App (2021)


## Install Docker on Amazon Linux 2
> sudo yum update -y

> sudo amazon-linux-extras install -y docker

> sudo service docker start

> sudo usermod -a -G docker ec2-user

> sudo systemctl enable docker

> docker info



## Download the code and Build the container
> sudo yum install -y git

> git clone https://github.com/Juli-BCN/pacman.git

> cd pacman

> docker build -t pacman .

> docker images



## Run, Test & Stop the Docker container
> docker run -d -p 80:80 pacman

> curl -L http://localhost

> docker ps

> :eyeglasses: docker stop *CONTAINER_ID*