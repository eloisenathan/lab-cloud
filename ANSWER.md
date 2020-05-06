# 1.
Qu'est-ce qu'une instance Virtual Machine ?
Une machine virtuelle est un fichier informatique qui se comporte comme un ordinateur réel. Il s’agit d’un ordinateur créé à l’intérieur d’un ordinateur. Elle s’exécute dans une fenêtre comme tout autre programme.

# 2.
Qu'est-ce qu'un VNET ?
VNET veut dire Virtual Network (Réseau Virtuel).
Il permet à un réseau de centres de données de fournir une structure de réseau la plus appropriée et la plus efficace pour les applications qu'il héberge. Il permet aussi de modifier cette structure selon les conditions, en utilisant un logiciel au lieu de faire des changements physiques dans les connexions au matériel. C’est la continuité du réseau physique d’une entreprise, mais dans le cloud.

# 3.
A quoi sert un NSG ?
Un NSG (Network Security Group) correspond aux matrices de flux. Il s’agit d’un pare-feu logiciel.
Ça permet de filtrer le trafic réseau à destination et en provenance des ressources Azure dans un réseau virtuel Azure.

# 4.
Quelles sont les 5 propriétés désirables du cloud ?
Quelles sont les 5 propriétés désirables du cloud ?
Les 5 propriétés sont :
-	Accès aux services par l'utilisateur à la demande.
-	Accès réseau large bande.
-	Réservoir de ressources (non localisées)
-	Redimensionnement rapide (élasticité)
-	Facturation à l'usage.

# 5.
Qu'est-ce que l'A/B Testing ?
L’A/B testing consiste à comparer deux versions d’une page web ou d’une application afin de vérifier laquelle est la plus performante. Ces variations, nommées A et B, sont présentées de manières aléatoires aux utilisateurs. 
Une partie d’entre eux sera dirigée vers la première version et l’autre sera affectée à la seconde. Par la suite, on fait une analyse statistique afin de tester l’efficacité des versions A et B sur différents indicateurs comme le taux de conversion. Cela permet donc de vérifier quelle version déclenche le plus de clics, d’abonnements, d’achats, etc. Ces résultats permettent de déterminer la meilleure stratégie marketing à adopter.

# 6.
Comment programmer le cloud ?
Les étapes pour programmer le cloud sont :
1)	stocker les données
2)	transférer les applications dans le cloud
3)	disposer d’une visibilité complète
4)	faire des amélioration

# 7.
Quelle est la technique pour faire un déploiement sans interruption de service ?
Pour faire un déploiement sans interruption de service, il faut isoler les machines de productions, découper les versions en plusieurs livraisons petites et moins complexes, automatiser les étapes de tests et passages en production d’une nouvelle version pour réduire les cycles.

# 8.
Qu'est-ce que le Canary release ?
Le canary release est un pattern qui permet de faire tester les dernières modifications réalisées à une tranche de population restreinte avant de réaliser un déploiement général de cette version. Il permet d’améliorer considérablement la qualité des mises en production.
Ce pattern permet aussi de tester les modifications et de s’assurer qu’elles fonctionnent correctement (fonctionnement, les bugs).
Il permet de laisser du temps pour mesurer les indicateurs qui indiqueront si les modifications apportées sont positives ou négatives pour l’entreprise.
Il est utile pour les entreprises qui fonctionnent dans un mode lean startup. 

# 9.
Comment changer de taille de machine virtuelle ?
On tape la commande suivante : VBoxManage.exe modifyhd "D:\VirtualBox\Windows 10bis.vdi" --resize 30000. Ici par exemple, on augmente le disque de 30Go.

# 10.
Qu'est-ce que le Blue/Green deployment ?
Le Blue Green deployment est un modèle de publication d'application qui permet de transférer progressivement le trafic utilisateur depuis la version antérieure d'une application ou d'un micro-service vers une nouvelle version pratiquement identique. Ces deux versions s'exécutent en même temps dans l'environnement de production.
L'ancienne version représente l'environnement bleu, tandis que la nouvelle version représente l'environnement vert. Une fois que le transfert du trafic entre l'environnement bleu et l'environnement vert est achevé, l'ancienne version peut être conservée pour une nouvelle restauration, ou peut être retirée de l'environnement de production.

# 11.
Citez deux avantages du PaaS sur le IaaS ?
2 avantages du PaaS :
- Une mise en production quasi instantanée.
- Une fluidité dans l'organisation

# 12.
Quelle est la différence entre le PaaS et le Serverless ?
Les applications Serverless évoluent instantanément, automatiquement et à la demande, sans configuration supplémentaire de la part du développeur ou du fournisseur. En revanche, ce n'est pas une caractéristique intrinsèque de PaaS.
Le serverless peut évoluer rapidement en faisant tourner de nouvelles instances de fonctions d'application à mesure qu'elles sont demandées. Il se réduit également rapidement en arrêtant les fonctions lorsqu'elles ne sont plus nécessaires ou lorsqu'elles ont fonctionné pendant une période de temps définie. Les applications basées sur PaaS ne peuvent pas évoluer si rapidement ou à un tel degré.

# 13.
Que veut dire Serverless ?
Le serverless est un modèle de cloud computing dans lequel le fournisseur de serveur gère les ressources attribuées au service client.
Cela signifie sans serveur.

# 14.
Citez les trois propriétés désirable du Serverless ?
Une application Web Serverless peut évoluer jusqu'à arrêter son activité, puis redémarrer en réponse à un événement en quelques secondes ou millisecondes. Certains fournisseurs Serverless ne facturent aux développeurs que la durée exacte d'exécution de leurs fonctions. Le temps de lancement des applications Serverless est très rapide.

# 15.
Comment s'appelle la plus petite unité de compute déployable en Serverless ?
