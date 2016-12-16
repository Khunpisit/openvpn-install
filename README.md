##openvpn-install
Forked from [cwaffles/ezopenvpn](https://github.com/cwaffles/ezopenvpn) and [Nyr/openvpn-install](https://github.com/Nyr/openvpn-install)

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

###New modify From forked repository

- Use cipher AES-256-CBC
- Support TLS 1.2 (OpenVPN 2.3+)
- Support SHA512
- Use Protocal TCP 
- Use Port 1194
- Default Google Public DNS [2]

###Installation
Run the script and follow the assistant:

`wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh`

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.

###I want to run my own VPN but don't have a server for that
You can get a VPS for just $5/month at [DigitalOcean](https://m.do.co/c/9a33fb00e021).

###Donations
You can donate via [PayPal](https://www.paypal.me/fordantitrust/5) or [Bitcoin](https://www.coinbase.com/fordantitrust). Thanks!
