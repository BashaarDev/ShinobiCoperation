# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.provider "virtualbox" do |vb|
    vb.name = "SC-W01"
    vb.memory = 512




    # network configuration
    # WHY DOENST IT WORK?! config.vm.network "public_network", bridge: 'eth1', ip: "192.168.1.100"




    #default scripts
    config.vm.provision "shell", path: "C:/Automation path/Projects/1# shinobi/scriptsdefault/install_nginx.sh"

  end
end
