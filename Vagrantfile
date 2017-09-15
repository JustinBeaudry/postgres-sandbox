Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/xenial64"
    config.vm.provision "shell", inline: <<-SHELL
     apt-get update
     apt-get install postgresql postgresql-contrib
    SHELL
end
