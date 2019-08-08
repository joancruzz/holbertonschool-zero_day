# 0x00. Vagrant

## Learning Objectives
1.  What is a virtual machine
2.  What is Vagrant
3.  Who wrote Vagrant
4.  What is Ubuntu
5.  What does “Ubuntu” mean
6.  How to use VMs with Vagrant
7.  What does the command uname do
8.  What is source code management
9.  What is Git
10. What is GitHub
11. What is the difference between Git and GitHub
12. How to create a repository
13. What is a README
14. How to write good READMEs
15. How to commit
16. How to write helpful commit messages
17. How to push code

## Prerequisites
### Install Vagrant on Mac OSx

```
$ vagrant init ubuntu/trusty64
```
Fill in with desired base:
```
base = "ubuntu/trusty64"
```
Start your virtual machine:
```
$ vagrant up
```
Enter virtual machine:
```
$ vagrant ssh
```

### Install Git
```
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
```
