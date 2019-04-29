# OpenVPN
Deploy and use the OpenVPN.
## Server start
Run the shell command following on Linux system
```Bash
git clone https://github.com/chaoxue-sysu/openvpn && cd openvpn && bash openvpn-install.sh
```
If you want add some configure files for other users, just rerun the script:
```Bash
bash openvpn-install.sh
```

## Client start
Download [OpenVPN Client](https://github.com/chaoxue-sysu/openvpn/raw/master/client/openvpn-install-2.4.7-I601.zip) and install on Windows system. The OpenVPN client for Andriod and iOS system can be downloaded from corresponding Application Store as well.
<br>
<br>
**Note** that some error may occur in TAP-Windows Adapter V9 on Windows OS, you can just reinstall with new version [TAP-Windows Adapter 9.21.2](https://github.com/chaoxue-sysu/openvpn/blob/master/client/tap-windows-9.21.2.zip) (see the [issue](https://forums.openvpn.net/viewtopic.php?t=26280)).
