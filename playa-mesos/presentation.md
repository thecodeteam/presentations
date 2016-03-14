![100%](https://upload.wikimedia.org/wikipedia/en/0/0d/Apache-Mesos-logo.jpg)
 
# [fit] Playa-Mesos

---

# What is Playa Mesos

A deployment tool helps you quickly create Apache Mesos test/dev environments.

    - All-in-one single node
    - Multi-node

with overridable defaults for:
- node memory & CPU resources
- installed software version

---

# Toolchain foundation
 
Required (recommended/minimum)
- VirtualBox (5.0.14+ / 5.010) 
- Vagrant (1..8.1+ / 1.3)

Optional
- Packer (0.9.0+ / 0.5)
- use VMware Fusion or Workstation 
    - with Vagrant plugin
    - (warning issue with 14.04.4)

---

#Step 1- Install VirtualBox

 ![20%](https://upload.wikimedia.org/wikipedia/commons/d/d5/Virtualbox_logo.png)
**brew cask install virtualbox**

**OR**
 ![30%](https://www.docker.com/sites/default/files/docker_toolbox_banner_icon.png)
install Docker Toolbox, with **docker-machine** from [https://www.docker.com/products/docker-toolbox](https://www.docker.com/products/docker-toolbox)

---

 ![70%](https://upload.wikimedia.org/wikipedia/commons/8/87/Vagrant.png)
 
#Step 2 - Install Vagrant

**brew cask install vagrant**

- Optional:

```bash
brew cask install vagrant-manager
brew install packer
```

Optional for external volumes 
- disable authentication and start SOAP web service

```bash
VBoxManage setproperty websrvauthlibrary null
/Applications/VirtualBox.app/Contents/MacOS/vboxwebsrv -H 0.0.0.0 -v
```

---

#Step 3 - Clone the Playa Mesos Repository

![20%](https://p4.zdassets.com/hc/settings_assets/558139/200117215/O4fX0WytFgMoaT6qIVasMg-Mesosphere_Logo_-_Horizontal_Lockup__RGB__Jumbo_.png)
**git clone https://github.com/mesosphere/playa-mesos.git**

OR

EMC{code} fork to enable external volume mounts
**git clone https://github.com/emccode/vagrant**

---

#Step 4 - Run script to test your environment

```bash
cd playa-mesos
bin/test
```

---

#Optional Step 5 - edit config.json

See documentation for instructions on choosing:

- all-in-one vs. multinode
- deployed software versions 

---

#Last step 

1. `vagrant up`
    -  if you elected options, add --provision flag

2. examine result:
    - Mesos [http://10.141.141.10:5050/#/](http://10.141.141.10:5050/#/)
    - Marathon [http://10.141.141.10:8080/](http://10.141.141.10:8080/ui/#/apps)

```bash
vagrant ssh mesos-master
ps -eaf | grep mesos
```

---

#Shutdown and recover Mac host resources

```bash
vagrant halt
vagrant destroy
```

---

#Demo
 
 ---
 
#Advisory

This can consume a lot of resource if you deploy multiple nodes.

Might want to shut down any other VMs before running a Playa Mesos cluster
- e.g. **docker-machine stop default** 
 