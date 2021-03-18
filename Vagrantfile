Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"
  config.vm.define "playground" do |instance|
    instance.vm.provider :virtualbox do |vm|
      vm.name = "playground"
    end
  config.vm.provision "shell", path: "script.sh"
  end
end

