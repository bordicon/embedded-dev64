# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "precise64"
  config.vm.network :private_network, :ip => "192.168.50.4"
  config.ssh.forward_agent = true
  config.vbguest.auto_update = true

  config.vm.provider "virtualbox" do |v|
    v.name = "Embedded Dev Box Maker (64-bit)"
    v.memory = 512
  end
end
