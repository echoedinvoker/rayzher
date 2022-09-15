# Lostash & Docker-Compose

## Why I use docker-compose to run logstash?

- Dockerize applications are portable and can be easily transferred to other devices to start without problems.
- When app is killed, it will restart automatically.

## Configurations

![Alt configurations](pic/bandicam%202022-09-15%2010-56-07-857.jpg)

- Compared to a typical logstash without dockerize, the difference is mainly in the input part.
  - dockerzide logstash cannot access external files or folders directly, so you must use bind mound to transfer external files inside the container.
