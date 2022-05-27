# I-Key

Ce projet est réalisé dans le cadre du module Communication Sans Fil en Licence 1 à l’Université
Nice Côte d'Azur.                                   


![image](https://user-images.githubusercontent.com/103360562/170486301-415fcfb0-f2a1-40a1-aa45-9db8b1e55d9e.png)



Motivations :

Après réflexion, plusieurs idées de projet nous sont venues à l’esprit, mais une seule a su retenir notre attention, c’est celle de la clé digitale.
En effet, nous voulions présenter un projet qui serait accessible et utile à tous.

Actuellement, nous pouvons constater que les locations de logements en ligne sont en hausse, notamment sur la Côte d’Azur où les touristes font plus de rentabilité en passant leur séjour dans un appartement ou une villa louée plutôt que dans une chambre d’hôtel.

![image](https://user-images.githubusercontent.com/103360562/167642877-ef3bf99a-3070-4bbc-adfd-d7ff66f73388.png)

Ceci étant dit, mettons nous à la place d’un propriétaire de plusieurs biens immobiliers à travers la France ou encore, à travers le monde. Notre but serait d’en tirer profit en les mettant sur la plateforme de location AirBnb, qu’on ne présente plus.

Se déplacer chaque jour pour donner les clés du logement à chaque locataire serait beaucoup trop fastidieux voir impossible.
C’est ici que notre idée prend forme : la clé digitale est générée par le prioritaire qui la partage avec le locataire via une application accessible à tous : Discord.

C’est à dire qu’à partir d’un téléphone, d’une tablette, d’une montre connectée, d’un ordinateur ou encore d’une Smart TV, la porte de notre logement peut s’ouvrir.

Néanmoins, cela implique certains inconvénients : une clé différente à chaque utilisation, une sécurité, une solution de secours, une clé possédant une date d’expiration correspondant au nombre de jours loués, etc.

Solutions techniques / Matériel :

Discord sera le début de notre circuit, il nous servira à :
- Générer la clé
- Supprimer la clé
- Vérifier la date d’expiration de la clé
- Créer une fiche utilisateur
- Vérifier la clé afin d’ouvrir la porte

The Things Network sera le 2ème élément de notre circuit, il s’occupera de l’envoi du paquet permettant l’ouverture de la porte en utilisant une Gateway lorsque la clé, vérifiée par Discord, est valide.

La carte LoRa sera le 3ème et dernier élément de notre circuit, il permettra :
- la réception du paquet émis par la Gateway The Things Network
- l’alimentation
- l’ouverture de la porte.

Schéma :

![image](https://user-images.githubusercontent.com/103360562/167645240-f6c1c6a5-a536-473f-9c78-55736968110a.png)





