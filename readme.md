# Vagrant barebone
Inspired by the one and only Stef Corputty and improved (I think) by me

## How to configure vagrant
in vagrant-config.yaml is where all the magic happens
in the config part you setup the global settings like domainname and the iprange.
in the vms part you setup the vms, the following settings are available
- hostname - required
- ip - required
- dsize - optional - size of extra disk
- autostart - optional - true or false, if false, the vm wont start unless you do vagrant up vmname


## bugs / features:
Last host cant have autostart false if you do want to ansible provision.