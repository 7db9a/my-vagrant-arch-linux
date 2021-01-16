## Dev

* Vagrant 2.01

* VirtualBox 5.01

Files from host are found at

`/vagrant/`

in the machine.

### Setup

Add the archlinux box where going to use. I found it at https://app.vagrantup.com/archlinux/boxes/archlinux.

`vagrant box add archlinux/archlinux`

Choose VirtualBox when prompted."

### Basics

`vagrant up`

To get into the machine.

`vagrant ssh`

Exit the machine.

`exit`

Suspend machine by stopping it and saving state.

`vagrant suspend`

Shutdown the machine.

`vagrant halt`

Reload after changes to Vagrantfile.

`vagrant reload`


**Other usefule commands**

Within the machine

`exit`

`vagrant destroy**

Use Ctrl + D or do execute `logout` in the machine.


