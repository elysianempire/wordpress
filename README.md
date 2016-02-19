# Instructions

These are instructions on how to get the docker-compose.yml in this repo running as fast as possible on Digital Ocean.

* Choose a one-click image with Docker
  * Be sure to pick a droplet with at least 1 Gb as MySQL will not start without enough memory.
  * Be sure to select your SSH public key when creating it.
* SSH into the image to install Rancher:

```
ssh root@<ip address>
```

Run this

```
git clone https://github.com/elysianempire/wordpress
cd wordpress
bash docker.sh
```
