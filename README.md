myVagrantBox
============

Vagrant box with chef recepies: for quick, clean, repeatable development.


knife solo

sudo apt-get install ruby1.9.1-d

sudo gem install knife-solo


init your kitchen

knife solo init myKitchen


install packages

knife cookbook site download python

tar xvzf python-1.4.6.tar.gz -C cookbooks

vagrant provision

vagrant ssh
