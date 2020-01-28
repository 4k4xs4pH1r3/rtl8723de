# rtl8723de
Realtek RTL8723DE module for Linux kernel version >= 5.0

Install:

    apt install git dkms -y && cd /usr/share && git clone https://github.com/smlinux/rtl8723de.git -b 5.0-up && dkms add ./rtl8723de && dkms install rtl8723de/5.1.1.8_21285.20171026_COEX20170111-1414 && depmod -a && reboot

Uninstall:

    cd /usr/share && rmmod -f 8723de && dkms uninstall rtl8723de/5.1.1.8_21285.20171026_COEX20170111-1414 && dkms remove rtl8723de/5.1.1.8_21285.20171026_COEX20170111-1414 --all && depmod -a && reboot
