# public-subnet
public facing subnetwork for (semi-centeralised) private services.

# Transfem Network (transfem.net)
  - built on Tailscale currently but hoping to host general Wireguard tunnel for more user capability.
  - i2p relay available with Tor and Yggdrasil outproxy
  - Test subnet connection with http://vps.rya-forel.ts.net / http://nyako.transfem.net / 100.102.121.9
  
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
 100.102.121.9:4444
 ```
 or using the subnet dns (not always as reliable for one reason or another):
 ```
 vps.rya-forel.ts.net:4444
 ```
 
 Feel free to host whatever service you want whether between friends or for testing. Please do not use to attack other users or attempt ssh, ftp, etc.
