Jupyterhub Deployment on Docker Swarm mode
==========================
# Clone
git clone this repo to /etc/jupyterhub:
```
sudo mkdir -p /etc/jupyterhub
sudo chown `id -u`:`id -u` /etc/jupyterhub
git clone https://github.com/zonca/deploy-jupyterhub-dockerswarm /etc/jupyterhub
```

# Nginx service
`cd /etc/jupyterhub` and edit nginx.conf, change `SERVER_URL` to your actual
value.
Then run `bash nginx_service.sh"

See <https://zonca.github.io/2017/10/scalable-jupyterhub-docker-swarm-mode.html>
