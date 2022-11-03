# DevOps Test Assignment

Assume you are given a server with:
* Ubuntu 20.04 LTS
* Drive with OS
* Drive for data

Using Ansible you need to provision a target server according to given requirements.
* set host name to eth-node
* install [nomad](https://www.nomadproject.io/) (it is enough to run in dev mode)
* you need to deploy an [ethereum node](https://github.com/ledgerwatch/erigon/tree/stable) as a container into a cluster and run it on a test net (Ropsten)
* you can create a dockerhub account and push your image there or use an existing one like [gatewayfm/erigon](https://hub.docker.com/r/gatewayfm/erigon)
* ledger data must survive restarts and also being placed on a mounted drive for data

Use Ansible for provisioning of this server.
It is ok to use proven modules.
An example how to start node and rpcdaemon can be found [here](https://github.com/ledgerwatch/erigon/blob/stable/docker-compose.yml)

Create a GitHub or GitLab repo for that and share with us.
