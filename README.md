# rtl8723de
Realtek RTL8723DE module for Linux kernel version >= 5.0

Install:

    sudo apt install git build-essential dkms -y && cd /usr/share/ && git clone -b extended https://github.com/lwfinger/rtlwifi_new.git && sudo dkms add ./rtlwifi_new && sudo dkms install rtlwifi-new/0.6 && sudo modprobe -r rtl8723de && sudo modprobe rtl8723de && echo "options rtl8723de ant_sel=3" | sudo tee /etc/modprobe.d/rtl8723de.conf && reboot -i
    
    
    
    
    
    
    
    
    
    
    
    
    
    http://ubuntuhandbook.org/index.php/2019/04/nstall-rtl8723de-wifi-driver-ubuntu-19-04/
 
