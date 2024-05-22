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