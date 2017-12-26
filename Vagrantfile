Vagrant.configure(2) do |config|
  config.vm.define "control" do |control|
    control.vm.box = "ubuntu/xenial64"
    control.vm.network "private_network", ip: "192.168.0.11"
    control.vm.hostname = "control"
    config.vm.provider "virtualbox" do |v|
        v.memory = 2048
        v.cpus = 2
    end
  end
  config.vm.define "lb01" do |lb01|
    lb01.vm.box = "ubuntu/xenial64"
    lb01.vm.network "private_network", ip: "192.168.0.12"
    lb01.vm.hostname = "lb01"
    config.vm.provider "virtualbox" do |v|
        v.memory = 2048
        v.cpus = 2
    end
  end
    config.vm.define "app01" do |app01|
    app01.vm.box = "ubuntu/xenial64"
    app01.vm.network "private_network", ip: "192.168.0.13"
    app01.vm.hostname = "app01"
    config.vm.provider "virtualbox" do |v|
        v.memory = 2048
        v.cpus = 2
    end
  end
  config.vm.define "app02" do |app02|
    app02.vm.box = "ubuntu/xenial64"
    app02.vm.network "private_network", ip: "192.168.0.14"
    app02.vm.hostname = "app02"
    config.vm.provider "virtualbox" do |v|
        v.memory = 2048
        v.cpus = 2
    end
  end
  config.vm.define "db01" do |db01|
    db01.vm.box = "ubuntu/xenial64"
    db01.vm.network "private_network", ip: "192.168.0.15"
    db01.vm.hostname = "db01"
    config.vm.provider "virtualbox" do |v|
        v.memory = 2048
        v.cpus = 2
    end
  end
end
