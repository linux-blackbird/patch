## Guide

1. download file `umountluks`
2. copy file `umountluks` ke direktori `/usr/local/bin`
3. berikan akses untuk eksekusi dengan perintah `sudo chmod +x /usr/local/bin/umountluks`
4. download file `luks-umounter.service`
5. copy file `luks-umounter.service` ke direktori `/etc/systemd/system/`
6. enable daemon dengan perintah `sudo systemctl enable luks-umounter.service`
7. reload daemon dengan perintah `sudo systemctl daemon-reload`
8. reboot untuk ujicoba
