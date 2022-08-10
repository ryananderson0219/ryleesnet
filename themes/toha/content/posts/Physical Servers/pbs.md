---
title: "Proxmox Backup Server"
date: 2020-06-08T06:00:20+06:00
hero: /images/posts/writing-posts/git.svg
menu:
  sidebar:
    name: Proxmox Backup Server
    identifier: proxmox-backup-server
    parent: physical-servers
    weight: 10
---

Below is my current setup for my Proxmox Backup Server. As you can see, this isn’t “enterprise-grade” hardware. This is consumer-grade hardware, but this is for a homelab with noise being the major factor. This saves me in electricity and also in noise level.

| Hardware | Price/Each | Quantity | Cost |
| ----------- | ----------- | ----------- | ----------- |
| [Chenbro Rackmount 4U Server Chassis](https://amzn.to/3Kt32bs) | $166.08 | 1 | $166.08 |
| [4-Bay Mobile Rack Backplane](https://amzn.to/3yYh4ek) | $112.53 | 1 | $112.53 |
| [ASRock Motherboard (Z390M-ITX/AC)](https://amzn.to/394Jh8w) | $-.-- | 1 | $-.-- |
| [Intel Core i5-9400](https://amzn.to/2YFdOYG) | $183.40 | 1 | $183.40 |
| [Netac 32GB (2x16GB) DDR4](https://amzn.to/3AnCioj) | $157.99 | 1 | $157.99 |
| [Samsung SSD 860 EVO 250GB](https://amzn.to/3lkfXRp) | $99.99 | 1 | $99.99 |
| [Western Digital 4TB WD Red Pro NAS](https://amzn.to/3nowRkp) | $119.99 | 4 | $479.96 |
| [Power Supply 500W 80 Plus Bronze](https://amzn.to/3FSpCXB) | $27.99 | 1 | $27.99 |
| | | | | |
| Total Cost |  |  | $1226.95+ |

#### Hardware
##### Case
[Chenbro Rackmount 4U Server Chassis](https://amzn.to/3Kt32bs)

[![Chenbro Rackmount 4U Server Chassis](https://m.media-amazon.com/images/I/91c-cJxs2rL._AC_SL1500_.jpg)](https://amzn.to/3Kt32bs)

##### Hard Drive Backplane
[4-Bay Mobile Rack Backplane](https://amzn.to/3yYh4ek)

[![4-Bay Mobile Rack Backplane](https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&MarketPlace=US&ASIN=B00OUSU8MI&ServiceVersion=20070822&ID=AsinImage&WS=1&Format=_SL250_&tag=ryleesnet-20)](https://amzn.to/3yYh4ek)

##### Motherboard
[ASRock Motherboard (Z390M-ITX/AC)](https://amzn.to/394Jh8w)

[![ASRock Motherboard (Z390M-ITX/AC)](https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&MarketPlace=US&ASIN=B07HYPSLLS&ServiceVersion=20070822&ID=AsinImage&WS=1&Format=_SL250_&tag=ryleesnet-20)](https://amzn.to/394Jh8w)


##### CPU
[Intel Core i5-9400](https://amzn.to/2YFdOYG)

[![Intel Core i5-9400](https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&MarketPlace=US&ASIN=B07MGZ9FJZ&ServiceVersion=20070822&ID=AsinImage&WS=1&Format=_SL250_&tag=ryleesnet-20)](https://amzn.to/2YFdOYG)


##### Memory
[Corsair Vengeance LPX 32GB](https://amzn.to/38Zuwnz)

[![Corsair Vengeance LPX 32GB](https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&MarketPlace=US&ASIN=B016ORTNI2&ServiceVersion=20070822&ID=AsinImage&WS=1&Format=_SL250_&tag=ryleesnet-20)](https://amzn.to/38Zuwnz)


##### NVMe (Boot Drive)
[Samsung SSD 860 EVO 250GB](https://amzn.to/3lkfXRp)

[![Samsung SSD 860 EVO 250GB](https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&MarketPlace=US&ASIN=B07864WMK8&ServiceVersion=20070822&ID=AsinImage&WS=1&Format=_SL250_&tag=ryleesnet-20)](https://amzn.to/3lkfXRp)


##### HHDs for Storage
[(4) Western Digital 4TB WD Red Pro NAS](https://amzn.to/3nowRkp)

[![Western Digital 4TB WD Red Pro NAS](https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&MarketPlace=US&ASIN=B07B1WK3N5&ServiceVersion=20070822&ID=AsinImage&WS=1&Format=_SL250_&tag=ryleesnet-20)](https://amzn.to/3nowRkp)


#### Software
[Proxmox Backup Server](https://proxmox.com/en/proxmox-backup-server)

[![Proxmox Backup Server](https://proxmox.com/images/proxmox/Proxmox_logo_standard_hex_400px.png)](https://proxmox.com/en/proxmox-backup-server)

