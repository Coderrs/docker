# docker
All Docker Related
- Get Virtual box from  - https://www.virtualbox.org/wiki/Downloads


# Setup Docker Ubuntu 1604 Xenial

## Reference : https://get.docker.com/
- curl -sSL https://get.docker.com/ | sh

## Reference : https://docs.docker.com/engine/installation/linux/ubuntulinux/#Ubuntu Xenial 16.04 (LTS)
- echo "deb https://apt.dockerproject.org/repo ubuntu-xenial main" >>/etc/apt/sources.list

## Install Compose https://docs.docker.com/compose/install/
- apt-get update && apt-get install docker-compose
or 
- curl -L https://github.com/docker/compose/releases/download/1.7.1/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose && chmod +x /usr/local/bin/docker-compose



