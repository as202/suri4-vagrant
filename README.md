# suri4-vagrant

This Vagrant file for make suricata from source code.

### Version  
OS: `Debian 9.7.0`  
Suricata: `4.1.2`  
Vagrant: `2.0.2`  

### Usage  
- Install a provider (Virtualbox/VMware/etc)  
- Install Vagrant (`sudo apt-get install vagrant`)  
- Starting  
```  
git clone https://github.com/as202/suri4-vagrant.git  
cd suri4-vagrant/  
vagrant up --provider=virtualbox  
```

### Tests  
Host OS: `Ubuntu 18.04 x86_64`   
Vagrant: `2.0.2`   


### Provide select  
```
vagrant up --provider=[vmware_fusion/virtualbox/etc]
```


### Reinstall
```
vagrant destroy -f && vagrant up
```

### Uninstall
```
vagrant destroy -f
```

### References  
1. https://app.vagrantup.com/generic/boxes/debian9/versions/1.9.2 -- Vagrant box
