---
title: infrastructure n°3
updated: 2022-10-15 10:46:18Z
created: 2022-10-14 10:50:12Z
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
Instance PLAY-NANO : 2vCPU, 4Go RAM = 19,71 * 3 = 59,13 €/mois
Stockage : 50 Go = 3.91 * 3 = 11,72 €
Adresse IP flexible = 1.46 * 3 = 4,38 €
Coût total = 75,23 €/mois
```

### 1 load balancer
```
Load Balancer LB-S : Trafic illimité - 200Mbit/s = 10.22 €/mois
IP alloué = 1.46 €
Coût total = 11.68 €/mois
```

### 1 serveur de base de données
```
Managed Database for MySQL
MySQL-8
Standalone (1 nœud)
Type DB-DEV-L : 4vCPU, 8Go RAM = 47.95 €/mois
Stockage : 10Go = 0.99 €
Coût total = 48.95 €/mois
```

## ***Coût total = 135,86 €/mois***
