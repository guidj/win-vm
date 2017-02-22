# Archlinux GPU Pass-through VM

TODO:

  - Fix NVIDIA driver code 43 issue

Main guide: 
  - GPU-Passthrough for 2 NVIDIA Cards: [TurluCode](http://turlucode.com/qemu-kvm-on-arch-linux-guide/)
  - Second: [TurluCode](http://turlucode.com/qemu-kvm-installing-windows-10-client/)
  
Exceptions:
  - Hugepages configuration: [ArchLinux-KVM](https://wiki.archlinux.org/index.php/KVM)


## Notes


  - During installation, it's likely your virtual drive will be invisible. Install drivers from the virtio-win.iso in order to see the disk. I installed *vioscsi* drivers for *win10/amd64*
