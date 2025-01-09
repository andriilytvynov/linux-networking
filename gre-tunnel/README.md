Before running this example, make sure you loaded `ip_gre` or `ipip` module into
linux kernel. (MacOS uses light linux VM, `ip_gre` and `ipip` are not avaliable.)
```bash
sudo modprobe ip_gre
sudo modprobe ipip
```
Verify that module has been loaded:
```
lsmod|grep ip_gre && lsmod|grep ipip
```
