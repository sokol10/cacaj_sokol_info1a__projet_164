Bienvenue dans le système de gestion des employés du Paléo
Ce projet de système de gestion des employés du Paléo est conçu pour faciliter la gestion des collaborateurs, des contrats, des départements, des adresses e-mail, des postes d'emploi et des numéros de téléphone au sein de l'organisation.

Prérequis
Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

PyCharm Community Edition : Un environnement de développement intégré (IDE) pour Python. Vous pouvez le télécharger depuis le site officiel de JetBrains : https://www.jetbrains.com/pycharm/

Git : Un système de contrôle de version décentralisé. Vous pouvez le télécharger depuis le site officiel : https://git-scm.com/downloads

Laragon : Un environnement de développement web pour Windows. Vous pouvez le télécharger depuis le site officiel : https://laragon.org/download/

Installation
Installez PyCharm Community Edition en suivant les instructions du programme d'installation.

Installez Git en suivant les instructions du programme d'installation.

Vérifiez que vous disposez de la dernière version de Git en ouvrant une fenêtre de commande et en exécutant la commande suivante :

css
Copy code
git --version
Installez Laragon en téléchargeant le programme d'installation et en suivant les instructions.

Ouvrez PyCharm Community Edition.

Cliquez sur "Open Project" (Ouvrir un projet) et sélectionnez le répertoire où se trouve le projet du système de gestion des employés du Paléo.

Une fois le projet ouvert, créez un environnement virtuel (venv) en allant dans "File" (Fichier) -> "Settings" (Paramètres) -> "Project: nom_du_projet" -> "Python Interpreter" (Interpréteur Python). Cliquez sur l'engrenage à côté de l'interpréteur actuel et sélectionnez "Add" (Ajouter) pour créer un nouvel environnement virtuel.

Installez les packages requis en exécutant la commande suivante dans la console de PyCharm :

Copy code
pip install -r requirements.txt
Lancez Laragon en exécutant le fichier "laragon.exe" et cliquez sur "Start" (Démarrer) dans l'application.

Dans la barre des tâches de Laragon, cliquez sur l'icône de base de données pour ouvrir l'outil de gestion de base de données.

Dans l'outil de gestion de base de données, allez dans l'onglet "Requêtes" et collez le contenu du fichier SQL fourni avec le projet. Exécutez la requête pour créer et peupler la base de données.

Revenez à PyCharm, ouvrez le fichier "run_mon_app.py" et exécutez-le pour lancer l'application.

Dans la console de PyCharm, vous verrez une URL indiquant où l'application est hébergée. Cliquez sur le lien pour accéder au site et naviguer dans les différentes catégories de gestion des employés du Paléo.

Vous êtes maintenant prêt
