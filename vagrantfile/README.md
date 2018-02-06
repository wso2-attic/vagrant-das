# Vagrantfile for WSO2 Data Analytics Server

This section defines the procedure to run Vagrant resources for a setup of WSO2 Data Analytics Server.

Please note that in order to run these Vagrant resources use, you need to install
[Oracle VM VirtualBox](http://www.oracle.com/technetwork/server-storage/virtualbox/downloads/index.html),
as Vagrant uses Oracle VM VirtualBox as the default provider.

Virtualization should be enabled in BIOS settings before building the boxes.

## How to run the Vagrantfile

1. Checkout this repository into your local machine using the following Git command.

```
	https://github.com/wso2/vagrant-das.git
```

2. Build Vagrant boxes for external MySQL database and Data Analytics Server using the Vagrant box automation resources.

3. Move to `vagrantfile` folder.

```
	cd vagrantfile
```

4. Spawn up the Vagrant setup.

```
	vagrant up
```
