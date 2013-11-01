[Installs OpenResty with LuaJIT](http://openresty.org/#Installation) on a [Vagrant box](http://www.vagrantup.com/) with a [Debian 7.2 base](http://www.debian.org/News/2013/20131012). I prefer Debian, but you might want to [pick a different](http://cloud-images.ubuntu.com/vagrant/) [base box](vagrantbox.es).

I'm new to Vagrant, and could not get provisioning through the Vagrantfile to work correctly. So, you will have to do this to set up a VM with OpenResty installed:

    vagrant up
    vagrant ssh
    cd /vagrant
    sudo ./install.sh

If you want a pre-packaged box built with the previous steps, do:

    vagrant box add debian7-openresty https://www.dropbox.com/s/odnew2tnliqft9o/debian7-openresty.box

Next step: [Getting Started with OpenResty](http://openresty.org/#GettingStarted)
