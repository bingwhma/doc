Openstack不会直接控制qemu-kvm，它会用一个叫libvirt的库去间接控制qemu-kvm。libvirt提供了跨VM平台的功能，它可以控制除了QEMU之外的模拟器，包括vmware, virtualbox， xen等等。
所以为了openstack的跨VM性，所以openstack只会用libvirt而不直接用qemu-kvm。libvirt还提供了一些高级的功能

referrenURL:
  http://blog.csdn.net/zhaihaifei/article/details/51018113
  
KVM虚拟化笔记  --参考url  http://liqingbiao.blog.51cto.com/3044896/1740702
