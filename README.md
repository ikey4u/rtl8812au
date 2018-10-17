# RTL8812AU driver for linux, mac and windows

For linux user, you could also use this driver supplied by another
[repo](https://github.com/gnab/rtl8812au).

```
git clone https://github.com/gnab/rtl8812au.git
cd rtl8812au/
make
sudo insmod 8812au.ko
sudo cp 8812au.ko /lib/modules/$(uname -r)/kernel/drivers/net/wireless
sudo depmod
```
