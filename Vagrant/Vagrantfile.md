```
Vagrant.configure("2") do |config|
 
  config.vm.box = "centos7"

Example for VirtualBox:

config.vm.provider "virtualbox" do |vb|
  vb.name = "CentOS_7"
  vb.memory = 2048
  vb.cpus = 2
end
```