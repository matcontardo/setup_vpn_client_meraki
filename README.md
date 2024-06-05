# Introduction

This action establishes connection for Cisco Meraki routers and L2TP/IPSec VPN protocols with PSK. Its use
is quite easy as you only need to provides it some variables as follows:

- **server**: Server IP
- **psk**: The preshared key
- **username**: Username
- **password**: Password
- **network_route**: The network you want to route through ppp0 tunnel.
- **test_ip**: An ip for final testing after connecting.