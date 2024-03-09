
# Rapport de Test

Nous avons testé l’application sur trois personnes différentes : Karolann, Shneider et Élies. Nous avons réclamé des informations précieuses au sujet de notre télécommande. Voici un résumé de chaque Test fait et ce qu’on a changé en fonction de l’avis des testeurs.

## Pré-Tests
Il est évident que nous avons testé notre télécommande avant de la faire tester à autrui. Voici les remarques personnelles qu’on a remarquées lors de la production :

**Power on**
Au début, nous avions mis un bouton Power on, mais on a réalisé plus tard que ce bouton portait à confusion, car il n’allumait pas vraiment le chrome cast. On a alors décidé de le remplacer par un bouton Cast; ce qui aidait plus facilement à comprendre que ce bouton servait à se connecter au chrome cast. Le bouton Start est par la suite devenu notre bouton Power on, car c’est lui qui allumait la télécommande.
**Volume**
Au début, on avait mis le volume pour qu’il décrémente par 0.05 / 1 par clique. On a opté après pour le remplacer à 0.04 lorsqu’on a appris que le chrome cast fonctionnait sur une échelle de 25; ça nous permet donc de décrémenter ou d’incrémenter de 1 a chaque clique du bouton.

**Karolann**
>Karolann a apprécié notre télécommande. Elle n’a pas eu de misère à se repérer dans la télécommande et elle n’a pas eu de problème lors de son utilisation. Elle nous a conseillé un changement en particulier : mettre un arrière-plan vert dans le bouton cast et Power on lorsque le chrome cast est connecté. Nous avons adoré l’idée, donc on l’a intégré dans notre application.

**Shneider**
>Shneider avait un petit problème lors de la connexion au chrome cast mais on a réalisé que l’erreur venait du fait qu’on avait oublié de se connecter au chrome cast; un problème qui n’était pas vraiment lié à la télécommande. Après la résolution du problème, il n’avait absolument aucun commentaire à part le fait qu’il était satisfait de la télécommande.

**Élies**
>Elies n’a pas eu de problème lors de l’utilisation. Il a testé la télécommande pendant 2-3 minutes et était satisfait avec le résultat. Il y avait cependant un petit problème lors de son utilisation. Parfois, lorsqu’il cliquait sur le bouton vidéo précédente, le chrome cast se perdait dans son chargement et le seul moyen de retourner en arrière était de cliquer sur vidéo suivante. Nous n’avons pas encore trouvé d’explication à ce problème, car c’est le même code utilisé pour le bouton vidéo suivante.



| Changement                                       | Objectif                                                         | Fonctionnalité                                        | État final                                           | Échec/Succès |
|--------------------------------------------------|------------------------------------------------------------------|-------------------------------------------------------|-----------------------------------------------------|--------------|
| Bouton Power on à Cast                           | Clarifier l'action de connexion au Chrome Cast                   | Connecter la télécommande au Chrome Cast              | Icône Chrome Cast utilisée                           | Succès       |
| Changement d'arrière-plan lors de la connexion   | Indiquer visuellement la connexion au Chrome Cast                | Changement de couleur du fond des boutons             | Arrière-plan vert lorsque connecté                   | Succès       |
| Correction du bogue du bouton vidéo précédente   | Assurer la fonctionnalité de navigation entre les vidéos         | Permettre de revenir à la vidéo précédente sans bug   | Problème non résolu                                  | Échec        |


## Information Projet

**Dispersion des tâches:**  
On a codé la majorité dans le même ordi(celui de yahya). Lorsque j'avais un problème, les autres venaient m'aider en codant directement dans mon ordi, ce qui explique pourquoi la majorité des commits venaient de moi. Cependant, la contribution fut en général la même et on a chacun contribué à une charge de travail similaire, autant dans le CSS que le HTML et le javascipt. Le travail a été réparti de sorte que tout le monde travaille en même temps sur différentes fonctions pour enfin les commit à la fin (ce qui expliquait les problèmes de merge) de même que s'entraider en temps réel.
    
**Code Javascript:**  
Les changements qu'on a fait dans le fichier CastVideos.js se trouvent entre la ligne 69 et 98

**Attentes:**  
Pour ce qui est de nos attentes, nous les avons dépassées en majorité, car nous pensons ne pas pouvoir utiliser la librarie, mais nous avons pu implémenter les fonctions que nous voulons telles que la fonction volume qui s'affiche à l'écran ainsi que le mute. Nous avons aussi implémenté des fonctions dont nous n'avons pas planifié lors de la conception telles que le bouton mute, mais il y a tout de même eu des limitations car nous avons enlevé quelques fonctionnalités planifiées au début comme le 10 secondes skip. Pour ce qui est de la télécommande, les attentes n'ont pas été atteinte, car nos tests ont suggéré de la confusion venant des boutons power et cast.

## Conclusion

En conclusion, les articles examinant les tests fonctionnels, les plans de test, les stratégies de test et l'exécution des tests ont grandement enrichi notre compréhension des pratiques cruciales dans le développement logiciel. Effectivement ces informations ont principalement retenu notre attention notamment pour le plan de test qui est une particularité que nous allons sérieusement envisager dans l’intégration de notre projet. Par exemple, pour définir les objectifs de test, nous pouvons discuter de différents moyens de comment un utilisateur peut trouver des méthodes de faire crasher l’application dans une fonction donnée et les noter sur une liste associée à cette fonction afin d’élaborer un plan pour l’exécution. Par la suite, nous assignons les tests en les répartissant entre les membres de l’équipe et on réajuste si nécessaire.

![IMG_8335](https://github.com/yahyamaw311/chromeCast/assets/158065120/8620d2d2-fdf7-429c-89a2-8296cf88cdf3)


## Maquette Projet 

**V1**
![manettev1](https://github.com/yahyamaw311/chromeCast/assets/112187141/bf19c0a0-fd9f-45eb-af2e-b7e5dddcffc8)

**V1.1**
![manettev2 2](https://github.com/yahyamaw311/chromeCast/assets/112187141/e403c859-2cdc-4125-909d-5582a6008f07)

**V1.2**
![manettev3](https://github.com/yahyamaw311/chromeCast/assets/112187141/ea1c8263-183a-47dd-b614-04a2e3720fb5)

**V2**
![Manettev2](https://github.com/yahyamaw311/chromeCast/assets/112187141/b07acda7-673c-4d30-8a53-c114a7853b3d)

**V3**
![MicrosoftTeams-image](https://github.com/yahyamaw311/chromeCast/assets/112187141/b3621c31-5253-4e37-9f58-7167e1acb87e)

**Version Final**
![Maquette_VersionFinal](https://github.com/yahyamaw311/chromeCast/assets/112187141/ffc32945-49c9-4ed1-96bb-cc8e2996b0f7)
