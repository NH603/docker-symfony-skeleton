# docker-symfony-skeleton

Docker Symfony Skeleton - install your favorite Symfony 3/4 framework and get started.

## Usage

1. create symfony application or use existing application, e.g.

        composer create-project symfony/skeleton foo
        cd foo

2. add this repository as remote

        git remote add docker https://github.com/cawolf/docker-symfony-skeleton.git

3. pull the necessary files

        git pull docker master

4. tweak the config files

5. build the image

        docker build . -t foo

6. create and run containers

        docker run -d -p 8000:80 foo
