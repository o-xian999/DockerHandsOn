# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "centos/8"
  config.vm.hostname = "test.local"
  config.vm.network :private_network, ip: "192.168.56.60"
  config.vm.provider :virtualbox do |vb|
    vb.name = "test"
    vb.customize ["modifyvm", :id, "--memory", "768"]
  end
end
