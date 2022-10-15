---
title: infrastructure n°3
updated: 2022-10-15 10:45:53Z
created: 2022-10-14 09:18:04Z
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
Ordinateur virtuel = Linux - Ubuntu
Instance = d2pls v5 : 2vCPU et 4Go de RAM = 61,40 * 3 = 184.20 €/mois
Stockage = HDD 64 Gio = 3.43 * 3 = 10.30 €/mois
Coût total = 194,55 €/mois
```

### 1 load balancer
```
1 Load Balancer type Standard
5 Règles Load Balancer = 18.95 € /mois
Règles NAT = 0.00 €
Données traitées = 2.25 Go/heure * 730h * 0.005 €/Go = 8.53 €/mois
Coût total = 27.48 €/mois
```

### 1 serveur de base de données
```
1 Base de données Azure pour MySQL
Gen 5, 2 vCore = 165.85 €/mois
Stockage = 10 Gio * 0139 € = 1,39 €/mois
Coût total = 167.24 €/mois
```

## ***Coût total = 389,27 €/mois***
