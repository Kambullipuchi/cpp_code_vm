Vagrant.configure(2) do |config|
  config.vm.box = "Ubuntu-14.04.3-64"
  config.vm.provision :shell, path: "shell.sh"
  config.vm.synced_folder "./code/", "/home/vagrant/code"
end