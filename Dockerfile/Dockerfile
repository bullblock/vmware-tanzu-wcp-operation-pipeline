# syntax=docker/dockerfile:1
FROM ubuntu:20.04
RUN apt update
RUN apt upgrade -y
RUN apt install git coreutils grep iputils-ping -y
ADD kubectl /usr/local/bin/kubectl
ADD kubectl-vsphere /usr/local/bin/kubectl-vsphere
RUN chmod a+x /usr/local/bin/*

