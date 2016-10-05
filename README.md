# Provision development machine [WIP]

## Installation

- Install VirtualBox:

  `https://www.virtualbox.org/`

- Install Vagrant:

  `https://www.vagrantup.com/`

- Install guest additions:

  `$ vagrant plugin install vagrant-vbguest`

- Create and provision the box:

  `$ vagrant up --provider virtualbox && vagrant provision`

- SSH into the box:

  `$ vagrant ssh`
