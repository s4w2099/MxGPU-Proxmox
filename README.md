# MxGPU-Proxmox
This repository contains Pre-compiled Proxmox VE Debian packages for AMD's MxGPU open source project (GIM) at https://github.com/amd/MxGPU-Virtualization.

To install a package in the host: 
* Add the "No-Subscription" or the "Enterprise" repository if you have a valid subscription.
* In the CLI type "apt update"
* Install the kernel header files with the following command "apt install proxmox-default-headers"
* After downloading the precompiled GIM drivers, install them by typing "apt install ./gim-dkms_X.X.X.K_all.deb
* Apt will automatically ask you to install the required dependensies.
* After driver installation you can start configuring the host.
* The guest VMs will also need a driver (amdgpu) in linux.

This documentation will be expanded in the future.
