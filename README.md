# GRO620 - Vision par ordinateur (S6R - APP6, E20)

Vous trouverez ici des fichiers Jupyter pour les activités procédurales et la résolution de la problématique.

Jupyter est un environnement qui permet de combiner de la documentation en
Markdown et des extraits de code en Python. Il est également possible d'ajouter
des éléments interactifs pour modifier le comportement du code. De plus, GitHub
fait un rendu (statique) des fichiers .ipynb, ce qui permet de visualiser
rapidement le contenu de ces fichiers.

Les images à utiliser pour la problématique se trouvent dans le dossier "images_prob/".

## Mise en route (Anaconda)

Les fichiers supposent que vous utiliserez Python 3 et la librairie OpenCV version 4. Pour vous assurer d'avoir les bonnes versions, on vous suggère fortement d'installer la distribution Anaconda (faites attention de bien sélectionner l'installation pour Python 3.7 !) :

[Anaconda Individual Edition](https://www.anaconda.com/products/individual)

Ensuite, vous devez installer les paquets OpenCV nécessaires à l'APP. Pour cela, depuis Anaconda Navigator, cliquez sur Environments et tapez "opencv" dans le champ "Search Packages..." en haut à droite :

![](images_doc/anaconda-opencv.png)

Cochez les paquets "libopencv", "opencv" et "py-opencv". Vérifiez qu'il vous propose bien la version 4. Vous n'avez ensuite qu'à appuyer "Apply" pour installer les paquets manquants.

Si Anaconda ne vous propose que la version 3.4.2, vous devrez plutôt ouvrir la console "Anaconda Prompt" puis utiliser la commande "pip install opencv-python".

## Google Colaboratory

Si vous n'arrivez pas à installer correctement Anaconda sur votre ordinateur, vous pouvez également utiliser Google Colaboratory en important le dossier au complet dans votre Google Drive. [https://colab.research.google.com/](https://colab.research.google.com/)
Cependant, il est possible que vous trouviez Google Colab plus lent que Jupyter
installé sur votre ordinateur. 

## Problématique

Un fichier de départ (très) simple est fourni pour débuter le travail: ["prob.ipynb"](prob.ipynb). Vous pouvez lancer ce calepin pour vérifier que votre installation de Jupyter fonctionne bien.

## Activités procédurales 

Pour commencer, ouvrez tout simplement ["proc_1.ipynb"](proc_1.ipynb) depuis Jupyter. Toutes les instructions s'y trouvent et vous pourrez éditer directement le fichier pour résoudre les activités.

