# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.provision :shell, path: "bootstrap.sh"

  config.vm.define "app" do |app|
  end
  
  config.vm.define "db" do |db|
  end

end
