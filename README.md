# AWS CI and Deploy Scripts
Simple CI scripts for ElasticBeanstalk with Docker.


## Prerequisits
Provision pip. My require 'sudo' permission.

```bash
 sudo apt-get install -y python-pip
 sudo -H pip install --upgrade pip
```

## Create Virtual Environment

Install Python Virtual Env prerequisits
```bash
 sudo pip install -r prerequisits
```

Create Virtual environment
```bash
 ./setup.sh
```

At this point, you should have virtual environment in ROOT folder.
To point Jetbrains IDE Python interpreter to Virtual environment

[Creating Virtual Environment](https://www.jetbrains.com/help/idea/creating-virtual-environment.html)  