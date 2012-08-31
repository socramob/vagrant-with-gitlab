Vagrant::Config.run do |config|
  config.vm.box = "lucid32-with-ruby1.9"
  config.vm.box_url = "file://./lucid32-with-ruby1.9.box"

  config.vm.provision :chef_solo do |chef|
    chef.cookbooks_path = "./cookbooks"
  end

  config.vm.forward_port 80, 4567 # method call
  config.vm.forward_port 3000, 3000
  config.vm.forward_port 8080, 8080
end
