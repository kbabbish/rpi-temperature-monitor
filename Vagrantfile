# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"

  config.vm.define "app" do |app|
	app.vm.provision :shell, path: "bootstrap-app.sh"
  end
  
  config.vm.define "db" do |db|
	app.vm.provision :shell, path: "bootstrap-db.sh"
  end

end
