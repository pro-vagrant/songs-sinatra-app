VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "gajdaw/sinatra"
  config.vm.network :forwarded_port, guest: 4567, host: 4567
end
