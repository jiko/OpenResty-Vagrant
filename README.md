OpenResty-Vagrant
===

Installs OpenResty with LuaJIT on a Vagrant box with a Debian 7.2 base. I chose the base box somewhat arbitrarily, so you might want to [pick a different one](vagrantbox.es).

I'm new to Vagrant, and could not get provisioning through the Vagrantfile to work correctly. So, you will have to do this to set up a VM with OpenResty installed.

    vagrant up
    vagrant ssh
    cd /vagrant
    sudo ./install.sh
