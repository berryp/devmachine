# Provision development machine [WIP]

## Installation

1. Install [VirtualBox](https://www.virtualbox.org/)
1. Install [Vagrant](https://www.vagrantup.com/)
1. Install guest additions: `$ vagrant plugin install vagrant-vbguest`
1. Create and provision the box: `$ vagrant up --provider virtualbox && vagrant provision`
1. SSH into the box: `$ vagrant ssh`
