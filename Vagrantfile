Vagrant.configure("2") do |config|
  config.vm.box = "generic/centos8"

  config.vm.define "machine"

  config.vm.network "private_network", ip: "192.168.56.10"

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "4096"
  end

  config.vm.provision "ansible" do |ansible|
    ansible.galaxy_role_file = "./provisioning/requirements.yml"
    ansible.playbook = "./provisioning/main.yml"
  end
end
