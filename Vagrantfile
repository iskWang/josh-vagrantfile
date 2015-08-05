# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure('2') do |config|
  config.vm.box      = 'ubuntu/trusty64'

  config.vm.synced_folder './work', '/vagrant', nfs: true

  # Set default network ip
  config.vm.network "private_network", ip: "192.168.50.10"

  config.vm.provision :shell, path: "bootstrap.sh", keep_color: true

   config.vm.provider "virtualbox" do |v|
     v.memory = 2048
     v.cpus = 2
   end
end
