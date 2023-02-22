Vagrant.configure("2") do |config|
    config.vm.define "vm1" do |vm1|
        vm1.vm.box = "rockylinux/8"
        vm1.vm.hostname = "web1"
        vm1.vm.provider "virtualbox" do |vb|
            vb.memory = 4096
            vb.cpus = 4
            vb.customize ["modifyvm", :id, "--firmware", "efi"]
        end
        vm1.vm.network :private_network, ip: "192.168.56.10"
    end
end
