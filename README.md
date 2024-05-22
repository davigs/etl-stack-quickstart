## Prerequisites
1. [Docker](https://docs.docker.com/engine/install/)
2. [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

The following command will clone the repo, copy `dev.env` to `.env` and run `docker compose up` to start Mage.

### Windows

```bash
git clone https://github.com/davigs/etl-stack-quickstart.git etl-stack-quickstart 
cd etl-stack-quickstart
cp dev.env .env
rm dev.env
docker compose up
```

### Projects

1. [mage.ai](http://127.0.0.1:6789)
2. [minio](http://127.0.0.1:9000)
3. [pgadmin](http://127.0.0.1:8080)