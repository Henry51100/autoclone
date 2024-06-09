
Auto Clone.py

Description

Auto Clone.py est un script Python conçu pour automatiser le processus de clonage de dépôts GitHub directement dans les environnements de développement intégrés (IDE) tels que PyCharm ou Visual Studio Code (VSC). Ce script simplifie le travail des développeurs en permettant de cloner rapidement plusieurs dépôts en une seule commande.

Fonctionnalités

	•	Clonage automatique de plusieurs dépôts GitHub.
	•	Lecture des URLs des dépôts à partir d’un fichier de configuration.
	•	Option pour choisir le répertoire de destination.
	•	Clonage direct dans PyCharm ou VSC.
	•	Gestion des erreurs et des duplications de dépôts.
	•	Des améliorations futures sont prévues.

Prérequis

	•	Python 3.12 ou version ultérieure
	•	git installé sur votre machine
	•	PyCharm ou Visual Studio Code installé

Installation

Clonez ce dépôt sur votre machine locale :

git clone https://github.com/henry/auto-clone.git
cd auto-clone

Installez les dépendances nécessaires (si applicable) :

pip install -r requirements.txt

Utilisation

	1.	Créez un fichier repos.txt dans le répertoire du script et ajoutez les URLs des dépôts GitHub que vous souhaitez cloner, chaque URL sur une nouvelle ligne.
Exemple de fichier repos.txt :

https://github.com/utilisateur/repo1.git
https://github.com/utilisateur/repo2.git
https://github.com/utilisateur/repo3.git


	2.	Exécutez le script :

python Auto Clone.py


	3.	Vous pouvez spécifier un répertoire de destination en utilisant l’option --dest :

python Auto Clone.py --dest /chemin/vers/destination


	4.	Pour cloner directement dans PyCharm ou VSC, utilisez les options spécifiques :

python Auto Clone.py --ide pycharm
python Auto Clone.py --ide vsc



Options de Ligne de Commande

	•	--dest: Spécifie le répertoire de destination pour les dépôts clonés.
	•	--ide: Spécifie l’IDE pour ouvrir les projets clonés (pycharm ou vsc).
	•	--help: Affiche l’aide et la liste des options disponibles.

Contribution

Les contributions sont les bienvenues ! Veuillez suivre les étapes suivantes pour contribuer :

	1.	Forkez ce dépôt.
	2.	Créez une nouvelle branche (git checkout -b feature-nouvelle-fonctionnalite).
	3.	Commitez vos changements (git commit -am 'Ajoute une nouvelle fonctionnalité').
	4.	Poussez votre branche (git push origin feature-nouvelle-fonctionnalite).
	5.	Créez une Pull Request.

Auteur

	•	Henry

Licence

Ce projet est sous licence MIT. Consultez le fichier LICENSE pour plus d’informations.
