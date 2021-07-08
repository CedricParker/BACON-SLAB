# B.A.Con S.Lab
Basic Ansible Configuration Standalone Lab

## Description
\###   Still in development Not-ready for production   \###

Using ansible to deploy a mini ovirt lab environtment.


## Table of Contents
List the sections that will appear on this README. Provide hyperlink to quickly jump between secitons. Each project does not have to provide the same table of contents,but should follow this format. Create sections that make sense to your project.
* [to-do](#to-do) 
* [Prerequisites](#prerequisites) 
* [Installation](#installation)  
* [Deployment](#deployment)
* [Contributing](#contributing)
* [Authors](#authors)
* [License](#license)

### To-do
short term to-do list to be usable.
```
overall deployment script/playbook
deploy ovirt-engine with answer file using ansible - currently not automated 
create an ansible vault instead of passwords file
move away from hard coded IP addresses
hunt down this error, laptop-2 command SpmStatusVDS failed: (13, 'Sanlock resource read failure', 'Permission denied') quick fix was changing the NFS share from 755 to 777. Adding Sanlock to KVM group did not resolve the issue as i thoug it would have. 
 
```
long-term to-do
```
master-laptop with configured repo and pxe
configure master laptop to provide internal/external Network

```
### Prerequisites
```
1 - laptop with centos 7 installed
3 - laptops with ovirtnode installed
1 - switch 
internet acces
```

### Installation
On the Master:
```
N/a
```
### Deployment
### Contributing
### Authors
Cedric L Parker - cedric.l.parker2.mil@mail.mil

### License
This project is licensed under GNU GPLv3. See [LICENSE.md](https://git.cybbh.space/1cybn-asc/infrastructure/devopsteam/-/blob/4f3b853e97a73e6a59e2afe3cfb420d8b9be7443/LICENSE) for more information. 







