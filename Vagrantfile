Vagrant.configure('2') do |config|
  config.vm.box = 'http://files.vagrantup.com/precise64.box'
  config.vm.provision :shell, :path => 'bootstrap.sh'
  config.vm.network :forwarded_port, :host => 9393, :guest => 9393
end
