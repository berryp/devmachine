# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.box_check_update = true
  config.vm.box_download_insecure = true
  config.vm.synced_folder "#{ENV['HOME']}/work", "/home/vagrant/work"

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "plays/base.yml"
  end
end
