    vagrant up

[installs OpenResty with LuaJIT](http://openresty.org/#Installation) in a [Vagrant box](http://www.vagrantup.com/) with a [Debian 7.3 base box](http://puppet-vagrant-boxes.puppetlabs.com/#tab-boxes) with VirtualBox 4.3.6 guest additions and [Puppet configuration management](http://puppetlabs.com/puppet/puppet-open-source). I prefer Debian, but you might want to [pick a different](http://cloud-images.ubuntu.com/vagrant/) [base box](http://www.vagrantbox.es/). Note, if `vagrant ssh` asks for a password, it's `vagrant`.

If you want a pre-packaged box built from this repository, do:

    vagrant box add debian7-openresty https://www.dropbox.com/s/odnew2tnliqft9o/debian7-openresty.box

Next step: [Getting Started with OpenResty](http://openresty.org/#GettingStarted)
