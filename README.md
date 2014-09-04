asus_ux32v_fan_control
======================
Installation of the Kernel Module:

- Clone the repository
- Move to the source directory of the kernel module
- execute "make all"
- copy the asus_fan.ko to your modules directory, for example: "/lib/modules/$( uname -r )/kernel
- execute "sudo depmod -a"

Now your able to load the module using "sudo modprobe asus_fan"
