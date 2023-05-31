# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.provider "virtualbox" do |vb|
    vb.name = "SC-W01"
    vb.memory = 512




    # network configuration
    config.vm.network "forwarded_port", guest: 80, host: 8080



    #default scripts
    config.vm.provision "shell", path: "C:/Automation path/Projects/1# shinobi/scriptsdefault/install_nginx.sh"

  end
end
