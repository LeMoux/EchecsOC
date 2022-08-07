
# EchecsOC
***Livrables du Projet 4 du parcours Python d'OpenClassrooms***

_Testé sous Windows 10 - Python version 3.9.1_



## Initialisation du projet


#### i. Windows :
Dans Windows Powershell, naviguer vers le dossier souhaité.
###### Récupération du projet

    $ git clone https://github.com/LeMoux/EchecsOC.git

###### Activer l'environnement virtuel
    $ cd ÉchecsOC 
    $ python -m venv env 
    $ ~env\scripts\activate
    
###### Installer les paquets requis
    $ pip install -r requirements.txt

###### Lancer le programme
    $ python main.py


---------

#### ii. MacOS et Linux :
Dans le terminal, naviguer vers le dossier souhaité.
###### Récupération du projet

    $ git clone https://github.com/LeMoux/EchecsOC.git

###### Activer l'environnement virtuel
    $ cd ÉchecsOC 
    $ python3 -m venv env 
    $ source env/bin/activate
    
###### Installer les paquets requis
    $ pip install -r requirements.txt

###### Lancer le programme
    $ python3 main.py


----------

#### iii. Générer un rapport flake8

    $ flake8 --format=html --htmldir=flake8_report

**Vous trouverez ensuite le rapport dans le dossier _'flake8-report'_.**

