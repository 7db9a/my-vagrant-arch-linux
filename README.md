## Dev

* Vagrant 2.01

* VirtualBox 5.01

Files from host are found at `/vagrant/`.

in the machine.

### Setup

Add the archlinux box. I found this one at https://app.vagrantup.com/archlinux/boxes/archlinux.

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

`vagrant destroy`

Use Ctrl + D or do `logout` in the machine.


