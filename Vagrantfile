# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.define :mr, primary: true do |mr|
    mr.vm.hostname = "mr"
    mr.vm.synced_folder ".", "/home/vagrant/mrmud"
  end
end