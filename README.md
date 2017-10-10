## Introduction Docker
![Docker logo](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/docker_logo.png)

what, why, how, setup, components and more

---

### Docker Statistics
dockercon17
![Docker ](https://raw.github.com/nsaboo/intro-docker/img/dockercon_2017.png)

- More than 14M Docker hosts
- More than 900k Docker apps
- 77,000% growth in Docker job listings
- More than 12B image pulls (accounting for 390,000% growth)
- More than 3,300 contributors
- More than 280 cities hold Docker meetups, which accounts for more than 170K members worldwide

- [moby](https://github.com/moby/moby) ranks 20th [gitstar-ranking](https://gitstar-ranking.com/repositories) by project on github

---

### what is docker
![Docker](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/docker.jpg)

Docker is an open-source project that automates the deployment of applications inside software containers.

---

### why Docker
![why Docker](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/why_docker.png)

---

#### container vs vm diagram
![container vs vm](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/container_vs_vm.jpg)

---

#### docker toolbox
brew cask install docker toolbox
![docker toolbox](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/brew_cask_install_docker_toolbox.png)

---
### docker components
brew desc docker
![docker](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/brew_desc_docker.png)

brew desc docker-machine
![docker-machine](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/brew_desc_docker_machine.png)

brew desc docker-compose
![docker-compose](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/brew_desc_docker_compose.png)

---

### Docker machine

![Docker machine](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/docker_machine.png)

A tool which makes it really easy to create Docker hosts on your computer,
on cloud providers and inside your own data center.
It creates servers, installs Docker on them, then configures the Docker client to talk to them.
Required for Mac, Windows users.

---

### Docker compose

![Docker compose](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/docker_compose.png)

A tool for defining and running complex applications with Docker
(eg a multi-container application) with a single file.

---

### Docker Components
![Docker Components](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/docker_components.png)

---

#### docker machine create virtualbox
<!-- ![virtualbox](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/docker_machine_create_virtualbox.png) -->

```
nsaboo-mn:~ nsaboo$ docker-machine create --driver "virtualbox" myBoxName
Creating CA: /Users/nsaboo/.docker/machine/certs/ca.pem
Creating client certificate: /Users/nsaboo/.docker/machine/certs/cert.pem
Running pre-create checks...
(myBoxName) Default Boot2Docker ISO is out-of-date, downloading the latest release...
(myBoxName) Latest release for github.com/boot2docker/boot2docker is v17.09.0-ce
(myBoxName) Downloading /Users/nsaboo/.docker/machine/cache/boot2docker.iso from https://github.com/boot2docker/boot2docker/releases/download/v17.09.0-ce/boot2docker.iso...
(myBoxName) 0%....10%....20%....30%....40%....50%....60%....70%....80%....90%....100%
Creating machine...
(myBoxName) Copying /Users/nsaboo/.docker/machine/cache/boot2docker.iso to /Users/nsaboo/.docker/machine/machines/myBoxName/boot2docker.iso...
(myBoxName) Creating VirtualBox VM...
(myBoxName) Creating SSH key...
(myBoxName) Starting the VM...
(myBoxName) Check network to re-create if needed...
(myBoxName) Found a new host-only adapter: "vboxnet0"
(myBoxName) Waiting for an IP...
Waiting for machine to be running, this may take a few minutes...
Detecting operating system of created instance...
Waiting for SSH to be available...
Detecting the provisioner...
Provisioning with boot2docker...
Copying certs to the local machine directory...
Copying certs to the remote machine...
Setting Docker configuration on the remote daemon...
Checking connection to Docker...
Docker is up and running!
To see how to connect your Docker Client to the Docker Engine running on this virtual machine, run: docker-machine env myBoxName
```

---

#### boot2docker.iso
![boot2docker.iso](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/boot2docker_iso.png)

---

### Docker swarm

![Docker swarm](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/docker_swarm.png)

A native clustering tool for Docker. Swarm pools together several Docker
hosts and exposes them as a single virtual Docker host. It scale up to multiple hosts.

---

### Docker distribution

![Docker distribution](https://raw.github.com/nsaboo/intro-docker/gh-pages/img/docker_distribution.png)

A (hosted) service containing repositories of images which responds to the Registry API.

---
