# -*- mode: ruby -*-
# vi: set ft=ruby :
hi i am suhail this is my repositry
Vagrant.configure("2") do |config|
  config.vm.define "server" do |server|
  server.vm.box = "ubuntu/trusty64"
 server.vm.network "private_network", ip: "192.168.56.100"
 server.vm.hostname = "server"

end

 config.vm.define "client" do |client|
 client.vm.box = "laravel/homestead"
 client.vm.network "private_network", ip: "192.168.55.110"
 client.vm.hostname = "client"
end
end
