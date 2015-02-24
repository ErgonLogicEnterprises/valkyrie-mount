# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"

  require "./mount.rb"

  config.vm.provision "shell", inline: 'echo $SUDO_USER', run: "always"

end
