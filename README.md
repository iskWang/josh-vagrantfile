# Josh Vagrantfile

Just a Ruby development environment :)

## Feature
* Ruby 2.1.2
* Ubuntu 14.04
* Integrate mysql and some rails package
* Taiwan ubuntu repo :D

## Require
* Virualbox (Recommand for mac: v4.3.20)
* Vagrant


##  Setup
	$ git clone git@github.com:iskWang/josh-vagrantfile.git
	$ cd josh-vagrant-box
	$ vagrant up

## Lets Develop!
	$ cd josh-vagrant-box/work
	$ (Being a code monkey)
	
## Login the server
	$ vagrant ssh
	(vagrant) $ cd /vagrant
	
## Mysql default setting (Sequel Pro)
	# You can change in bootstrap.sh 
	MySQL Host: 127.0.0.1
	Username: root
	Password: 12345678

	# Or Vagrantfile :)
	SSH Host: 192.168.50.10
	SSH User: vagrant
	SSH Password: vagrant

## Ref.
[Vagrant] (https://www.vagrantup.com)

[Vagrant + VirtualBox VM aborted after sleep](http://stackoverflow.com/questions/28524815/vagrant-virtualbox-vm-aborted-after-sleep)

[Virutalbox v4.3.20] (http://download.virtualbox.org/virtualbox/4.3.20/)

	