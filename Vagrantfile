# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "precise64"
  config.vm.box_url = "http://files.vagrantup.com/precise64.box"
  config.vm.network :forwarded_port, guest: 4000, host: 4000, auto_correct: true
  config.vm.provision :shell,
    :inline => "sudo apt-get -y install build-essential && sudo /opt/vagrant_ruby/bin/gem install jekyll rdiscount --no-ri --no-rdoc"
  config.vm.provision :shell,
    :inline => "cd /vagrant && jekyll serve"
end