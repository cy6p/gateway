# Gateway

A simple side gateway solution.

## Quick start

```bash
# fix file permissions lost by git
sudo chmod 0640 config/dae/config.dae

# get the latest image
sudo docker compose pull

# start up
sudo docker compose up
```

## How it works

Use candy to join a virtual private network and be able to access the socks5 services provided in the network.

Use socks5 in the candy network as a dae node and distribute traffic based on domain name and IP.
