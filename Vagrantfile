Vagrant.configure(2) do |config|
  config.vm.define "kernel-update" do |srv|
    srv.vm.box = "centos8"
    srv.vm.synced_folder "./", "/vagrant"
    srv.vm.hostname = "kernel-update"
    srv.vm.network(:private_network, ip: "192.168.56.8")
    srv.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
      vb.cpus = "2"
    end
  end
end
