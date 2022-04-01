Vagrant.configure("2") do |config|
  config.vm.define :servidor2Axi do |servidor2Axi|
  servidor2Axi.vm.box = "centos/stream8"
  servidor2Axi.vm.network :private_network, ip: "192.168.100.5"
  servidor2Axi.vm.hostname = "servidor2Axi"
  end
  config.vm.define :firewallAxi do |firewallAxi|
  firewallAxi.vm.box = "centos/stream8"
  firewallAxi.vm.network :private_network, ip: "209.191.100.3"
  firewallAxi.vm.network :private_network, ip: "192.168.100.3"
  firewallAxi.vm.hostname = "firewallAxi"
  end
  config.vm.define :servidor3Axi do |servidor3Axi|
  servidor3Axi.vm.box = "centos/stream8"
  servidor3Axi.vm.network :private_network, ip: "192.168.100.4"
  servidor3Axi.vm.hostname = "servidor3Axi"
  end
end
