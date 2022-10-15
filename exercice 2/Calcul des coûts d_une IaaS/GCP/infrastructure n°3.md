---
title: infrastructure n°3
updated: 2022-10-15 10:44:39Z
created: 2022-10-14 10:21:21Z
latitude: 48.85661400
longitude: 2.35222190
altitude: 0.0000
---

**3 serveurs avec les ressources suivantes :**
> 4 Go de RAM minimum
> 2 vCPU
> 50 Go de stockage disque par serveur

**1 load balancer qui répartit 5 Mb/s de données équitablement vers les 3 serveurs ci-dessus**

**1 service de base de données managé**
> 8 Go de RAM minimum
> 2 vCPU
> 10 Go de stockage disque

### 3 serveurs
```
Compute engine
OS : Free Debian
Type : e2-medium (2 vCPU, 4Go RAM) = 34.24 * 3 = 102.73 USD
Stockage : 2.32 * 3 = 6.96 USD
Coût total = 109.69 USD/mois
```

### 1 load balancer
```
Cloud Load Balancing and Network Services
Number of forwarding rules = 5 = 21.35 USD
Inbound Data Processed = 625 KB = 0 USD
Outbound Data Processed = 625 KB = 0 USD
Coût total = 21.35 USD/mois
```

### 1 serveur de base de données
```
CLOUD SQL FOR MySQL
Type : db-standard-2 (2vCpu, 7.5 GB de RAM)
Stockage : HDD 10 Go
Coût total = 115.33 USD/mois
```

## ***Coût total = 246,37 USD/mois***
