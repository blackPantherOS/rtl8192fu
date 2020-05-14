# rtl8192fu

- Asus USB N13 C1 Wifi device with RTL8192FU/RTL8725AU - 5.1.x kernel support

The riginal source was rtl8192FU_rtl8725AU_WiFi_linux_v5.8.6_33905.20190604_COEX20190509-0d01.tar.gz
but the original code does not compatible with > 5.1.x kernel series

- Added patch for build with never kernel.

Use simple 
----------
make

Kernel module name will is:
---------------------------
8192fu.ko

Load module:
------------
insmod 8192fu.ko
