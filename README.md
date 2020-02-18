# qemu_usage

## Info
full system emulation and user mode emulation.

qemu-x86_64 and  qemu-system-x86_64

## Installation Debian
```
sudo apt-get install qemu-kvm qemu virt-manager virt-viewer libvirt
sudo apt-get install qemu-kvm qemu virt-manager virt-viewer 
sudo apt-get install qemu-system 
sudo apt-get install qemu-user 
```

## Create virtual machine
```
qemu-system-x86_64 -hda linux.img -boot d -cdrom
```

## Boot VM
```
qemu-system-x86_64 -boot d -cdrom Porteus-Kiosk-4.9.0-x86_64.iso -m 2048 lubuntu-19.10-desktop-amd64.iso
```
