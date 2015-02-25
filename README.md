# server-provisioning
Server initiate scripts

This script will be installed at "/var/local/sysinit"

Sample Json config
```
{
    "network": [
        {
            "type": "public",
            "nic": "eth0",
            "mac": "00:0C:29:DD:9C:73",
            "address": "192.168.0.64",
            "subnet": "255.255.255.0",
            "gateway": "192.168.0.1",
            "dns": [
                "8.8.8.8",
                "8.8.6.6"
            ]
        },
        {
            "type": "private",
            "nic": "eth1",
            "mac": "22:34:56:78:90:ab",
            "address": "1.2.3.4",
            "subnet": "255.255.255.0"
        }
    ],
    "hostname": "asdf1234"
}

```
