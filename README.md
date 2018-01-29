# Provisioning

## Goal
The goal of this excerise is to set up MongoDB in a VM for easy deployment.

## Intallation 
Clone the repository:

```bash
git clone git@github.com:HirakN/ProvisioningLab.git
cd ProvisioningLab
```

### Virtual Box and Vagrant
To begin, download the following programs and install them:

[Virtual Box](https://www.virtualbox.org/wiki/Downloads)

[Vagrant](https://www.vagrantup.com/downloads.html)

Virtual Box is used to provide the vitual machine environment and vagrant will be used to get the functionality without the clutter.

### Starting the VM
To start the VM and set up the db simply enter:
```bash
vagrant up
```

### Shutting down

You can shut down the server by running:

	vagrant destroy
	
>Note: All changes will be lost upon shutdown

If you want to save the state of your machine you can intead use:

	vagrant supsend
	
>Note: This will use up resources on your machine.