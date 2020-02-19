# Install
```
virt-install \
--name falcon-1 \
--ram 1024 \
--disk path=/var/lib/libvirt/images/falcon1.img,size=8 \
--vcpus 1 \
--virt-type kvm \
--os-type linux \
--os-variant ubuntu18.04 \
--graphics none \
--location 'http://archive.ubuntu.com/ubuntu/dists/bionic/main/installer-amd64/' \
--extra-args "console=tty0 console=ttyS0,115200n8"
```
```
virt-install --name=Ubuntu-16.10 --vcpus=1 --ram=1024 --cdrom=/Data/ISO/ubuntu-16.10-desktop-amd64.iso --disk path=/var/lib/libvirt/images/ubuntu-16.10.img,size=10 --os-type=linux
```

# Commands
```
virsh list --all
virsh edit Ubuntu
virsh start Ubuntu
virt-viewer Ubuntu

virsh destroy debian
```
