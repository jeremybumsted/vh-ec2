## Vault Hunters Docker Compose


### **About**
---
This is config-as-code for a minecraft container deployment running on AWS EC2 used for the Vault Hunters minecraft mod.
Copied and modified from https://github.com/wotupfoo/minecraft-container/blob/vault-hunters/docker-compose.yml

The docker-compose service uses the latest image from [wotupfoo/vault-hunters](https://hub.docker.com/r/wotupfoo/vault-hunters/tags)


### **Usage**
---

The service is deployed using standard `docker-compose` commands

```shell
docker-compose start
```

It requires a mount directory of `vault-hunters` in the working directory of the compose file to store persistent server data and is freely modifiable.