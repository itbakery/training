name: inverse
layout: true
class: center, middle, inverse

---
## Ceph
---
layout: false
## Prepare
- Nested kvm
```bash
sudo su -
vi /etc/modprobe.d/kvm.conf

options kvm_intel nested=1

reboot
```
- Virtualbox + extensions
  - https://www.virtualbox.org/wiki/Downloads
  - Extensions pack http://download.virtualbox.org/virtualbox/5.1.6/Oracle_VM_VirtualBox_Extension_Pack-5.1.6-110634.vbox-extpack

---
