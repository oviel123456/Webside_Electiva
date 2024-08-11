Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/bionic64"
    config.vm.network "private_network", ip: "192.168.56.10"
    config.vm.hostname = "devops-server"

    # Asegúrate de que Vagrant no inserte una nueva clave SSH
    config.ssh.insert_key = false
end