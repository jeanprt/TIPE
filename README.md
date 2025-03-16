# TIPE  
---
Suivi des recherches

#### 31/01/2025
--
 - Outils à utiliser :
 - <a href="https://scholar.google.fr/schhp?hl=fr&as_sdt=0,5">Google Scholar</a>
  - Recherches du jour :
      - [Réduction de bruit active sur GoogleScholar](https://scholar.google.fr/scholar?hl=fr&as_sdt=0%2C5&q=r%C3%A9duction+de+bruit+active&btnG=&oq=r%C3%A9duction+de+bruit+)
  - Idées de sujet du jour :
    - _**Réduction de bruit active**_ :
      1. Comment ca marche? Active, passive ?
      2. Comment inverser la phase d'un signal : analogique numérique ?
      3. Si la réduction de bruit active produit un "anti-son", produit-il une fatigue auditive ? car même si - par - = +, la réduction par production de bruit peut peut être endommager l'oreille aussi.
      4. Qu'en est-il du mode "Transparence" ?
      5. Quelle différence entre les casques et les écouteurs ?
      6. Faire un système DIY
    - Micros Neumann KU100 pour étudier les différents casques.

-
#### 2/02/2025
Recherches du jour :

- Réduction de bruit active brevetée par Bose en 1996 au départ pour le domaine de l'aviation exclusivement.

- La qualité de la réduction de bruit dépend du nombre de micros, de leur qualité, de la vitesse de la carte, le nombre d'écoute de l'environement extérieur (700/secondes). La qualité est bonne à partir de 4 micros par casque.

- La réduction fonctionne d'autant mieux que les bruit à atténuer sont simples. Le grondement d'un moteur dans un avion, voiture, train sont simples à atténuer face à des discussions ou à des bruits de clavier qui sont plus imprévisibles.


-
#### 7/02/2025
Recherches du jour :

Vibiscus :  

- [Article sur Techniques de l'ingénieur.](./Articles\ TI/Vibiscus - la fine fleur de la réduction de bruit | Techniques de l'Ingénieur.pdf)
- Startup qui concoit des matériaux réduisant le son de manière active. Analogie avec les pixels d'un écran : Chaque partie du matériaux peut être modifié pour attenuer un son. Alternative à la réduction de bruit active par création de son en opposition de phase.

Orosound start'up Francais production de casques à réduction de bruit active très efficace. STAGE ? A CONTATCTER !


-
#### 14/02/2025

Lien avec L'aBRI UBordeaux. Peut être utile pour mener des expérimentations sur le son, son acquisition et son traitement numérique.    

Liens donnés par Mr Raimi pour les recherches
- Technique de l'ingénieur
- sci hub
- universalis
- google scholar
- hal.archives-ouvertes
- sudoc abes
- https://hal.science
- https://bupdoc.udppc.asso.fr/
- https://culturesciencesphysique.ens-lyon.fr/
- https://eduscol.education.fr/sti/si-ens-paris-saclay
- https://pixees.fr/
- https://www.olymphys.fr/public/index.php

Dans notre salle de classe, le néon faisait un bruit dérangeant. Je l'ai analysé : fréquence de 50 Hz. Plus tard en TP de Chimie, le bloc d'alimentation d'un agitateur magnétique produisait un son aigü vers un multiple de 50 Hz. Fort de ces deux expériences, je me suis dit qu'il devait exister un lien entre ces bruits et la fréquence d'oscillation du courant.

 - [Vulgarisation bruit des Néons, Brut](https://www.brut.media/fr/videos/culture-lifestyle/musique/le-scintillement-et-le-bourdonnement-du-neon)

 - Recherches sur le dB et le dBA...
 - [Recherches Sur Hal `Réduction de bruit`](https://hal.science/search/index?q=r%C3%A9duction+de+bruit+active)
 - [Recherches sur TI `réduction de bruit active`](https://www-techniques-ingenieur-fr.docelec.u-bordeaux.fr/search.html?types=822005e&sc=3f&dm=7fff&limit=10&query=r%C3%A9duction+de+bruit+active&page=1)


-
#### 21/02/2025  

Idées et infos de la semaine:  
1. Néons  
- Gaz  
  
-
#### 14/03/2025
Recherches sur les vibrations induites par les transformateurs electriques.
A maitriser avant de se pencher sur le sujet :  


- [ ] Comment marche un transformateur
- [ ] principe interne et fonctionnement 
- [ ] Equations de fonctionnement
- [ ] dégager un modèle simple

Vidéo pour comprendre :

- transformateurs sont au coeur de notre vie
- dispositif pour transferer l'énergie electrique
- seuelement en courant alternatfi et pas en continu
- Là où les appareils traditionnels ont comme mesure l'ampère et le volt, on utilise le voltampère
- deux bobines séparés par un noyeau de fer
	- pas le même nombre de spires des deux côtés
	- champs magnétiques des bobines transporté par le fer doux
- transformateur élévateur / abaisseur
-  à cause de la resistance du cable : petite tension => bcp de pertes, grande tension moins

- transformateur est un convertisseur statique permettant de transformer une tension sinusoiïdale en unte autre tension sinusoïdale

### 15 et 16/03/2025
Visionnage de différentes vidéos pour commencer à comprendre.
Les transformateurs jouent un rôle important dans notre quotidient puisqu'ils permettent de réhausser et d'abaisser la tension du courant pour arriver jusque dans nos maisons.

#####Notion de courant triphasé :
Pour des soucis de performances (puissance et moindres pertes) le courant triphasé est préférable au monophasé.
Le courant triphasé possède trois phases décalées de 120° et d'un neutre (d'où 4 fils lors du transport) contre une phase et un neutre pour le monophasé. Les trois phases ont la même fréquence ($f = 50\text{ Hz}$ en France).  
<img src="images/3_phase_AC_waveform.png" align="center" width="300px" alt="Allure des courbes du courant triphasé">
*fig. 1 : Allure des courbes du courant triphasé*

Le courant triphasé alimente des machines ayant besoin de plus de puissance. Moteurs asynchornes.
Montages en étoile Y ou en triangle Δ.

#####Chemin de l'électricité en général :
1. Énérgie prduite dans une centrale (nucléaire en France) délivre du courant triphasé à 12 kV
2. Tension haussée par un *transformateur élévateur* à 230 kV pour le transport sur des longues distances dans les cables pour éviter les pertes par effet Joule (Ri^2)
3. Transport
4. Transformateur abaisseur à 69 kV pour distribution au réseau de moyenne distribution
5. Lien avec les industriels qui possèdent leur propres transformateurs abaisseurs. Ils utilisent souvent le triphasé.
6. Transformateur abaisseur à 12.4 kV pour la sous distribution entre les quartiers par exemple
7. Transformateurs abaisseurs pour des chaque rue / quartier à 480/280V en triphasé ou 240/120V en monophasé.

<img src="images/reseau.png" width="600px" alt="Schéma du réseau de distribution électrique">  
*fig. 2 : Schéma du réseau de distribution électrique*

---
## À Faire
- [ ] Contacter Orosound stage été
- [ ] Contacter collègue de Julie Géan
