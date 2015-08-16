VAGRANT_API_VERSION = "2"

Vagrant.configure(VAGRANT_API_VERSION) do |config|

  config.vm.box = "ubuntu/trusty64"

  config.vm.network "private_network", type: "dhcp"

  config.vm.provision :ansible do |ansible|

    ansible.playbook = "playbook.yml"

   end

end

