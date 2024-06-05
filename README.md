# Introduction

This action establishes connection for Cisco Meraki VPN routers using the L2TP/IPSec protocols with PSK. Its use
is quite easy as you only need to provides it some variables like:

- **server**: Server IP
- **psk**: The preshared key
- **username**: Username
- **password**: Password
- **network_route**: The network you want to route through ppp0 tunnel.
- **test_ip**: An ip for final testing after connecting.