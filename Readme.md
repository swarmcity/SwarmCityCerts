[Swarm City](https://github.com/swarmcity/sc-boardwalk-production/blob/master/images/icons/icon-48x48.png?raw=true "Swarm City")

[![Build Status](https://travis-ci.org/swarmcity/SwarmCityCerts.svg?branch=master)](https://travis-ci.org/swarmcity/SwarmCityCerts)

# Swarm City Certs

## Introduction
The certs repo automates the process of obtaining the SSL certificates, the certificates ensure the communication from the site to the API is secure. We are obtaining the SSL from ‘Let’s Encrypt’ via CertBot. https://letsencrypt.org/

## Install dependencies

- git

   Install [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) commandline tool.

- docker

   Install [docker](https://docs.docker.com/engine/installation). The community edition (docker-ce) will work. In Linux make sure you grant permissions to the current user to use docker by adding current user to docker group, `sudo usermod -aG docker $USER`. Once you update the users group, exit from the current terminal and open a new one to make effect.

- docker-compose

   Install [docker-compose](https://docs.docker.com/compose/install)
   
**Note**:- Make sure you can run `git`, `docker ps`, `docker-compose` without any issue and without sudo command.
