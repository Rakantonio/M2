# Quel type de cloud pour quels besoins ?

## Cas n°1 : ELDO
> Développe un SaaS pour la mise en relation de professionnels du BTP
> 
> Développe un CRM pour les professionnels du BTP
> 
> Nombre d’employés : 60
### Solution – Type de Cloud : Public et PaaS
- Eldo est une start-up compose de 60 employés. L’entreprise peut donc décider de louer des
serveurs dédiés à l’entreprise chez un fournisseur cloud, ainsi que des serveurs pour
héberger les sites et CRM.
- Le modèle PaaS est le plus adapté. Les sites et applications pourront être mises en ligne
rapidement pour que professionnels/particuliers puissent en bénéficier rapidement.
- Le développement et l’ajout de nouvelles fonctionnalités sur les applications seront plus
faciles grâce à l’unification des services (base de données, OS, outils de développement utiles
au bon fonctionnement de l’application, …).
- L’entreprise pourra faire des économies au niveau du recrutement d’experts informatiques.
Exemple similaire : TripAdvisor

--- 

## Cas n°2 : MySecureProtect
> Objets connectés en liaison avec les serveurs de l’entreprise
> 
> Nombre d’employés : 150
### Solution – Type de Cloud : Hybride et SaaS
- L’entreprise aura son infrastructure sur le cloud et en local. Le but d’avoir son infrastructure
en local est de pouvoir sécuriser les données sensibles des utilisateurs (nom, prénom,
adresse, …). L’entreprise pourra alors passer des certifications ISO qui pourront rassurer les
utilisateurs par rapport à ses données.
- Le modèle de cloud hybride permettrait également à l’entreprise d’avoir un plan de
continuité/reprise d’activité permettant aux objets connectés et applications de toujours
fonctionner, ainsi que pour ne pas perdre les données clients si une catastrophe venait à se
produire (incendie sur l’infrastructure local par exemple).
- Le modèle SaaS permettra de gérer plusieurs points comme :
  - L’application mobile puisse être accessible depuis n’importe où par tous les
utilisateurs.
  - L’entreprise pourra faire des économies en achetant des serveurs à l’utilisation.
  - Les 2 infras seront interconnectées, permettant à l’entreprise de lier les données
sensibles des utilisateurs avec les applications.
  - Il faudra que l’entreprise renforce la méthode d’authentification des utilisateurs à
leur application en utilisant des services proposés par le fournisseur de cloud comme
SAML par exemple. Il faudra également chiffrer les données qui transitent avec un
TLS par exemple.

--- 

## Cas n°3 : Paul
> Reprendre le contrôle de ses données
> 
> Nombre d’employés : N/A
> 
> Stocker les photos et y accéder depuis de nombreux appareils
> 
> 800Go de données et stockage évolue relativement peu.
### Solution – Type de Cloud : Privé avec CozyCloud et modèle SaaS
- CozyCloud permet de réunir les informations personnelles comme les photos dans le
domicile numérique de Cozy.
- CozyCloud offre la possibilité d’utiliser toutes les applications comme Cozy Drive pour croiser
les données. Les données seront donc regroupées.
- Un stockage de 1000 Go sera suffisant pour un coût de 9.98€/mois.
- Ses photos seront accessibles depuis téléphone et ordinateurs
- CozyCloud offre une solution d’auto-hébergement (Cloud personnel)
Exemple similaire : Google drive

--- 

## Cas n°4 : Entreprise de soutien aux armées.
> Moderniser les infrastructures informatiques.
> 
> Confidentialité
> 
>Diversité de service, quantité de serveurs, stockages et réseaux évoluent
>
> Nombre d’employés : 5000
### Solution – Type de Cloud : Privé et Private PaaS
- L’entreprise traite des informations confidentielles qui peuvent mettre en péril tout un pays.
Ils ont donc besoin d’avoir un contrôle total sur leur serveurs et applications.
- Étant une grande entreprise, elle devra mettre en place ses propres datacenters redondés
pour avoir un plan de continuité, de reprise d’activités car les données doivent être toujours
disponibles.
- L’entreprise pourra également passer les différentes certifications ISO de sécurité pour
mettre en place les bonnes pratiques de sécurité dans l’entreprise.
- Ce sera une infrastructure « On-Premises » car les équipements seront opérés par
l’entreprise. Il faudra que l’entreprise prévoie le budget nécessaire pour subvenir à ses
besoins en termes de quantité de serveurs, de stockages et de réseaux.
- Pour les services, l’entreprise pourrait partir sur un modèle de PaaS privé afin d’unifier le
fonctionnement des services au sein de l’organisation.
- Le PaaS privé doit être mis en place en déployant des applications et des services adaptés sur
le cloud privé de l'organisation.

---

## Cas n°5 : TheFoodStore
> Petite entreprise
> 
> Veut publier un site e-commerce rapidement afin de générer les ventes
> 
> Nombre d’employés : 5
### Solution – Type de Cloud : Public et SaaS
- L’entreprise pourra utiliser un service d’hébergement et de création de site web sur le cloud.
- Il n’y aura donc pas d’installation de logiciel en locale
- L’entreprise paiera un abonnement pour héberger son site, gérer ses ventes et ses clients.
- Le site sera accessible de partout depuis tous les appareils.
Exemple : utilisation de shopify pour gérer son site.

---

## Cas n°6 : DeliverEats
> Plateforme permettant de commander et se faire livrer des repas.
> 
> Application mobile et site internet pour passer commande.
> 
> Application mobile pour servir de GPS au livreur.
> 
> Tablette pour recevoir les commandes.
### Solution – Type de Cloud : Public et SaaS
- L’entreprise pourra utiliser un cloud public pour héberger les machines physiques chez le
fournisseur. Elle pourrait également louer des serveurs physiques dédiés.
- Elle fera des économies de coûts en ne payant que les ressources qu’elle utilise comme chez
AWS par exemple. Son architecture sera mutualisée.
- Le modèle sera du SaaS. L’entreprise pourra payer pour bénéficier de services comme Twilio
qui fournit des services de communications unifiées via des API.
Exemple similaire : Deliveroo qui utilise Twilio également.

---

## Cas n°7 : Onenvepa
> Entreprise de télévendeurs.
> 
> Besoin de nouveau système de gestion des informations et des futurs clients.
> 
> Travaillent partout dans le monde.
> 
> Nombre de télévendeurs : beaucoup trop
### Solution – Type de Cloud : Multi Cloud et SaaS
- Onenvepa est une grande entreprise qui travaille partout dans le monde. Il faut donc que ses
infrastructures soient fonctionnelles en 24/7.
- Ils pourront s’appuyer sur plusieurs fournisseurs pour dupliquer ses infrastructures et ses
services. Ainsi, si un fournisseur tombe, les infrastructures pourront basculer sur d’autres
fournisseurs permettant aux services de continuer à tourner.
- Le modèle sera du SaaS car les applications et services doivent être accessibles depuis
n’importe où dans le monde.
- Les ressources utilisées pourront évoluer et l’entreprise pourra faire des économies en ne
payant que les applications qu’elle utilise.