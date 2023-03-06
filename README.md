# public-subnet
public facing subnetwork for (semi-centeralised) private services.


  - built on Tailscale currently but hoping to host general Wireguard tunnel for more user capability.
  - i2p relay available with Tor and Yggdrasil outproxy
  - Test subnet connection with http://xoxyla.nya OR http://nyako.transfem.net
  - add issue request or message on matrix at @xoxyla:matrix.org for `*.nya` domain. 
    - need requested domain name, and hostname/ipv4/ipv6
    - ~~clearnet option available as well but privacy is iffy as it is provided via http://000webhost.com~~
  - supports internal ipv6 usage as well.
 ## Connecting:
 ### Connecting to the subnet is relatively easy, first you have to install the Tailscale service.
 Windows: 
 ```
 winget install tailscale.tailscale
 ```
 
 Linux: 
 ```
 apt install tailscale
 ```
 Both: 
 ```
 tailscale login --auth-key=ke8jxY6CNTRL
 tailscale up
 ```
 HTTP proxy available at:
 ```
 xoxyla.nya:4444
 ```
 
 Feel free to host whatever service you want whether between friends or for testing. Please do not use to attack other users or attempt ssh, ftp, etc.
