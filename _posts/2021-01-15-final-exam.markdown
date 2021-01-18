---
layout: post
categories: jekyll update
title:  "FINAL EXAM: Hands-On"
---
![FE](https://user-images.githubusercontent.com/75419236/104277678-372d7480-54e2-11eb-9ef0-5074969f62b8.png)
1. Fork this repository [https://github.com/ajcanlas-tip/sysad2-12021.git](https://github.com/ajcanlas-tip/sysad2-12021.git)

2. Clone your new repository in your VM *https://github.com/< your username >/sysad2-12021.git*

3. Create a branch named "final-exam" and checkout in that branch.

4. Create an Ansible playbook that does the following with an input of a config.yaml file and structure inventory file.

	 4.1 Clone your prelim exam repository

	 4.2 Install and configure one enterprise service that can be installed in Debian,Centos and OpenSuse servers

	 4.3 Install and configure one monitoring tool that can be installed in Debian, Centos and OpenSuse servers (if it is a stack there should be option of different host)

	 4.4 Change Motd as "Ansible Managed by * < username > *"

5. push and commit your final-exam branch in the VM (no need for ansible.cfg upon pushing)

6. request a pull request from that branch in GitHub

7. For your final exam to be counted, please paste your repository link as an answer in this exam.

*Note: Extra points if you will implement the said services via containerization.*  

### OUTPUT:  
Github:https://github.com/eacena-tip/sysad2-12021/tree/final-exam
├── README.md
├── ansible.cfg
├── playbook.yml
├── final-exam.yml
├── inventory
└── roles
│ ├── ftpcentos
│ │   ├── README.md
│ │   ├── defaults
│ │   │   └── main.yml
│ │   ├── files
│ │   ├── handlers
│ │   │   └── main.yml
│ │   ├── meta
│ │   │   └── main.yml
│ │   ├── tasks
│ │   │   └── main.yml
│ │   ├── templates
│ │   ├── tests
│ │   │   ├── inventory
│ │   │   └── test.yml
│ │   └── vars
│ │   └── main.yml
│ ├── rolescentosnagios
│ │   ├── README.md
│ │   ├── defaults
│ │   │   └── main.yml
│ │   ├── files
│ │   ├── handlers
│ │   │   └── main.yml
│ │   ├── meta
│ │   │   └── main.yml
│ │   ├── tasks
│ │   │   └── main.yml
│ │   ├── templates
│ │   ├── tests
│ │   │   ├── inventory
│ │   │   └── test.yml
│ │   └── vars
│ │   └── main.yml
│ ├── ftpdebian
│ │   ├── README.md
│ │   ├── defaults
│ │   │   └── main.yml
│ │   ├── files
│ │   ├── handlers
│ │   │   └── main.yml
│ │   ├── meta
│ │   │   └── main.yml
│ │   ├── tasks
│ │   │   └── main.yml
│ │   ├── templates
│ │   ├── tests
│ │   │   ├── inventory
│ │   │   └── test.yml
│ │   └── vars
│ │   └── main.yml
│ ├── rolesdebiannagios
│ │   ├── README.md
│ │   ├── defaults
│ │   │   └── main.yml
│ │   ├── files
│ │   ├── handlers
│ │   │   └── main.yml
│ │   ├── meta
│ │   │   └── main.yml
│ │   ├── tasks
│ │   │   └── main.yml
│ │   ├── templates
│ │   ├── tests
│ │   │   ├── inventory
│ │   │   └── test.yml
│ │   └── vars
│ │   └── main.yml
│ ├── clone_centos
│ │   ├── README.md
│ │   ├── defaults
│ │   │   └── main.yml
│ │   ├── files
│ │   ├── handlers
│ │   │   └── main.yml
│ │   ├── meta
│ │   │   └── main.yml
│ │   ├── tasks
│ │   │   └── main.yml
│ │   ├── templates
│ │   ├── tests
│ │   │   ├── inventory
│ │   │   └── test.yml
│ │   └── vars
│ │   └── main.yml
│ ├── clone_nagios
│ │   ├── README.md
│ │   ├── defaults
│ │   │   └── main.yml
│ │   ├── files
│ │   ├── handlers
│ │   │   └── main.yml
│ │   ├── meta
│ │   │   └── main.yml
│ │   ├── tasks
│ │   │   └── main.yml
│ │   ├── templates
│ │   ├── tests
│ │   │   ├── inventory
│ │   │   └── test.yml
│ │   └── vars
│ │   └── main.yml
│ ├── clone_opensuse
│ │   ├── README.md
│ │   ├── defaults
│ │   │   └── main.yml
│ │   ├── files
│ │   ├── handlers
│ │   │   └── main.yml
│ │   ├── meta
│ │   │   └── main.yml
│ │   ├── tasks
│ │   │   └── main.yml
│ │   ├── templates
│ │   ├── tests
│ │   │   ├── inventory
│ │   │   └── test.yml
│ │   └── vars
│ │   └── main.yml
│ ├── motd
│ │   ├── README.md
│ │   ├── defaults
│ │   │   └── main.yml
│ │   ├── files
│ │   ├── handlers
│ │   │   └── main.yml
│ │   ├── meta
│ │   │   └── main.yml
│ │   ├── tasks
│ │   │   └── main.yml
│ │   ├── templates
│ │   ├── tests
│ │   │   ├── inventory
│ │   │   └── test.yml
│ │   └── vars
│ │   └── main.yml
│ ├── ftpopensuse
│ │   ├── README.md
│ │   ├── defaults
│ │   │   └── main.yml
│ │   ├── files
│ │   ├── handlers
│ │   │   └── main.yml
│ │   ├── meta
│ │   │   └── main.yml
│ │   ├── tasks
│ │   │   └── main.yml
│ │   ├── templates
│ │   ├── tests
│ │   │   ├── inventory
│ │   │   └── test.yml
│ │   └── vars
│ │   └── main.yml
│ └── rolessusenagios
│ ├── README.md
│ ├── defaults
│ │   └── main.yml
│ ├── files
│ ├── handlers
│ │   └── main.yml
│ ├── meta
│ │   └── main.yml
│ ├── tasks
│ │   └── main.yml
│ ├── templates
│ ├── tests
│ │   ├── inventory
│ │   └── test.yml
│ └── vars
│ └── main.yml
