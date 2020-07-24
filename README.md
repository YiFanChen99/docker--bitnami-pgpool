# docker--bitnami-pgpool

## Using docker-compose with bitnami/pgpool:4

1. Get postgresql node(s) up and ready
1. Config environments on `docker-compose.yml`
1. Config `pgpool.conf` if needed
1. ` docker-compose up -d `

or

## Using Dockerfile to build an image and run

1. Config `pgpool.conf`, `pool_hba.conf`, and `pool_passwd` if needed
1. ` docker build -t $IMG_NAME ./ `
1. ` docker run -it --rm $IMG_NAME `
