# docker-symfony-skeleton

Docker Symfony Skeleton - install your favorite Symfony 3/4 framework and get started.

## Supported tags and respective `Dockerfile` links

* `v1.0.1`, `latest` [Dockerfile](https://github.com/cawolf/docker-symfony-skeleton/blob/v1.0.1/Dockerfile)

## Usage

1. create symfony application or use existing application, e.g.

        composer create-project symfony/skeleton foo
        cd foo

2. download this repository as ZIP

3. extract `Dockerfile` and the `docker` folder into your project

4. tweak the config files

5. build the image

        docker build . -t foo

6. create and run containers

        docker run -d -p 8000:80 foo

## TODO

* add `docker-compose.yml` template for production and development environment (with mounted app)
