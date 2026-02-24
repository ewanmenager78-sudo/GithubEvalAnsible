le fichier default contient tout les éléments de la connexion a la BDD

le handler nous alertes du restart de apache sur les vm Ubuntu/debian rocky/redhat, il nous indique également le restart de mariadb

dans task on créer la bdd avec l'utilisateur root et un mot de passe, et ensuite ont créer un autre utilisateur ensuite on télécharge wordpress, et on copie le contenue de wordpress vers root, ont configure ensuite php

ensuite dans Template on a l'affichage de connexion a la bdd.

dans test on a le playbook de test.

et dans vars on a les chemins d'accès et les packages pour la BDD et apache2
