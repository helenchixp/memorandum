Linux(Centos) nmtui Command

How to set the ssh in virtural box.

use 'nmtui' command, and set the 'enp0s3' and 'enp0s8'.
``` bash
nmtui
```

Edit Connection -> enp0s3

------------Edit Connection--------------

Profile name: enp0s3

IPv4 CONFIGURATION <Automatic>
IPv6 CONFIGURATION <Ignore>

[X]Automatically connect
[X]Available to all users

----------------------------------------

Edit Connection -> enp0s8

------------Edit Connection--------------

Profile name: enp0s8

IPv4 CONFIGURATION <Manual>
     Addresses 192.168.XX.XXX
IPv6 CONFIGURATION <Ignore>

[X]Automatically connect
[X]Available to all users

----------------------------------------

