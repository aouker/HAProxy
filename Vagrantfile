Vagrant.configure("2") do |config|

    config.vm.box = "centos/7"
	config.vm.define :www1 do |www1|
    	    www1.vm.hostname = "www1"
    	    www1.vm.network "public_network", ip: "192.168.1.242"
        end

        config.vm.define :www2 do |www2|
            www2.vm.hostname = "www2"
            www2.vm.network "public_network", ip: "192.168.1.243"
        end

        config.vm.define :www do |www|
            www.vm.hostname = "www"
            www.vm.network "public_network", ip: "192.168.1.241"
        end
end
