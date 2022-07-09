# Ansible Semester 6 Infrastructure

## TLDR
Semester 6 ansible repo for my personal learning, since my semeseter is done I will be archiving this and take the "good" parts and put it in its own repository

## Intoduction

This is my Ansible Repostory for semester 6 IT infrastructure while studying on Fontys University of applied sciences. 

This repository has gotten A little bit messy over time some, playbooks and roles are better quality then others cause of time restriction. 

### Goal

The main goal of this repository was just to get really comfortable with Ansible, and working and using Ansible to actually configure and manage a infrastructure. And for that it succeeded. 


## Directory Structure

###  Root 
 Directory root contains the main playbooks and inventory these playbooks make use of other ansible files within, roles and collections. 

 The names speak pretty much for themselfes

 - Kubernetes.yml
   - Configures my kubernetes cluster setup
- Kea.yml
  - Configures my Kea DHCP server
- Terraform.yml
  - Configures an Terraform machine
- Produciton.yml
  - Configures the base configuration needed for this environment
- Bind9.yml
  - Configures bind9 DNS server


## Playbooks
Contains adhocs style playbooks some of these could be converted into roles but cause of time constraint it was easier to create them first in an more adhoc style and later maybe convert them

## Roles
Contains Ansible roles within this semester I have created most of the roles myself however the bind9 roles is cloned from [Github](https://github.com/bertvv/ansible-role-bind). 

## Barrel
Is a littlebit like my programming junk drawer, these were roles i started but couldn't really get right in the time frame so i dropped them and but them there for later use

## Host vars
So i was able to set specific hostvars for the clients within my ansible cluster

## Collection
Is for AWX to install any needed Plugins


# The Future of this repository

Everybody who finds this can use it tbh, I will probarly see which roles and playbooks i particuarly like and put them in seperated repositories whenever I get the time and after cleaning them up a littlebit. And making them a bit more proffesional. 

The quality in this repository really goes from left to right sometimes. 

Thank you for reading and have a nice day



