# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "debian/jessie64"

  config.vm.network "private_network", ip: "192.168.7.11"

   config.vm.provider "virtualbox" do |vb|
     vb.memory = "512"
   end
end
