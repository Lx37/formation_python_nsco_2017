------------------

# Python

![python](http://i.imgur.com/bc2xk.png)


------------------


# Programme des 5 jours:


  * Lundi 24 avril 2017 (matin et après-midi):
    * Installation (distribution Anaconda + packages)
    * Bases de la programmation Python
    * Calcul scientifique : Base numpy

  * Mardi 25 avril 2017 (matin et après-midi)
    * Calcul scientifique : NumPy
    * Visualisation : module Matplotlib
    * Manipulation de fichiers
    * Manipulation de répertoire (os, glob, re)

    
------------------


# Programme des 5 jours (suite):

  * Mercredi 26 avril 2017 (matin)
    * jupyter notebook
    * scipy
    * pandas

  * Jeudi 27 avril 2017 (matin):
    * Pandas suite
    * Seaborn (visualisation de données statistiques)

  * Vendredi 28 avril 2017 (matin):
    * stat en python avec StatsModel
    * Interfaçage Python/R software rpy2
    * exo final




------------------

# Pour anticiper les réclamantions

  * ça va aller un trop vite
  * les support de court sont légers.
  * tout ne va pas vous être utile.

# En revanche:

  * il existe de très bon support de court
  * les formateurs sont des beaux gosses


------------------

# Historique

  * Créer en 1989 par Guido Van Rossum.
  * Version 1.5 en 1999
  * Aujourd'hui 3.6
  * Debut du python scientifique en 2005 par Travis Oliphant avec numpy
  * Aujourd'hui 6e language
  * Aujourd'hui 1er language pour l'analyse de donnée.

------------------

# Pourquoi python:
  * language ancien donc mur
  * language généraliste
  * language orienté object
  * philosophie = simplicité de relecture du code.
  * le même language pour web, admin, analyse data, ...
  * libre
  * grande commmunauté
  * facile à enseigner
  * y'a tout
  * communauté qui fait dons de ses codes.


------------------

# Utilisateurs de python

  * Google
  * Nasa
  * Instagram
  * Nous


------------------

# Idée en vrac

  * un language **inteprété**
  * Pas d'environement de développement, éditeur, debuggeur (il faut en trouver un, spyder pour nous)
  * Peu de librairie officielle
  * les modules scientifique sont developées indépendement
  * Il existe plusieur interpréteur (CPython, IronPython, PyPy, Jython)
  * On utilise le plus connu CPython


------------------

# Installation

# C'est pas si facile car:

  * Il y a plusieurs version 2.7 et 3.5, 3.6, on ne sait pas laquelle choisir.
  * Sous OSX et linux c'est déjà installé masi c'est souvent pas la bonne version
  * Il faut aussi installer toute les librairies dont on a besoin
  * les libairie scientifique sont en C/C++/fortran il faut un compilateurs!!
  * python fournit un installateur de pacquet officiel pip (site pypi) mais ça marche pas quand c'est compilé.
  * parfois c'est sur github
  * arbre de dépendance complexe.



------------------

# Sous OSX

  * il y a déjà python mais pas les numpy, scipy, Qt
  * homebrew
  * macport
  * conda


------------------ 

# Sous windows

  * python.org + http://www.lfd.uci.edu/~gohlke/pythonlibs/
  * winpython (choix à Gerland)
  * conda


------------------

# sous linux (ubuntu, debian)

  * c'est déjà installé
  * python (=python2) et python3 (=python3.4)
  * certain paquet avec:
    ```
      sudo apt-get install python-numpy
      sudo apt-get install python3-numpy
    ```
  * d'autre avec :
    ```
      pip install numpy
      pip3 install numpy
    ```
  * conda

------------------

# Environement virtuel

  * permet pour chaque projet de choisir une version de python + chaque librairie
  * conda intègre les environement virtuel


------------------

# Installation de conda.

  * Installer le paquet seaborn
```
  conda install seaborn
```



------------------

# URL à lire tout seul

  * www.opentechschool.org
  * http://www.scipy-lectures.org/
  * http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/
  * https://bitbucket.org/lothiraldan/presentations/src/27b389b125fe/AtelierPythonUTBM/?at=default



