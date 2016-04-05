# docker-compose-aria2
Docker Compose file for https://hub.docker.com/r/nemoalex/aria2/

## How to use

1. Install [Docker](https://docs.docker.com/linux/step_one/)

2. Install [Docker Compose](https://docs.docker.com/compose/install/)

3. Clone the repository

  ```
  git clone https://github.com/NemoAlex/docker-compose-aria2.git
  ```
4. Edit `docker-compose-aria2/docker-compose.yml` and `docker-compose-aria2/etc/aria2.conf`

> Note: We strongly recommend setting a rpc-secret key in aria2.conf

5. Run aria2

  ```
  cd docker-compose-aria2
  docker-compose up
  ```

6. Make sure everything's right. Run `docker-compose up -d` to start the daemon.
