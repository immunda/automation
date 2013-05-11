Vagrant::Config.run do |config|
    config.vm.box = "raring64"
    config.vm.box_url = "http://mirror.airwired.org/boxes/raring-server-cloudimg-vagrant-amd64-disk1.box"
    config.vm.provision :puppet
    config.vm.network :hostonly, "10.11.12.13"
end
