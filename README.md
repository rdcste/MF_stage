# Manipulation et traitement des données brutes satellitaires de niveau 1


<hr>


Manipulation et traitement des données brutes satellitaires de niveau 1
Météo-France

Pour toutes questions contacter meteo-spatiale@meteo.fr

Tous les noms de produits, logos et marques sont la propriété de leurs propriétaires respectifs.
Tous les noms d'entreprises, de produits et de services utilisés sur ce site Web sont uniquement à des fins d'identification.

## Auteurs

* [**Jean-Baptiste Hernandez**](mailto://jean-baptiste.hernandez@meteo.fr) - [Météo-France](https://meteofrance.com/)
* [**Rudy Coste**](mailto://rudy.coste@meteo.fr) - [Météo-France](https://meteofrance.com/)
* [**Olivier Membrive**](mailto://osi-saf.manager@meteo.fr) - [Météo-France](https://meteofrance.com/)


## Installation

Le moyen le plus simple et le meilleur pour installer ces packages est Git. Les utilisateurs peuvent cloner ce référentiel.
Une fois que vous avez ouvert un terminal/une invite de commande, vous devez accéder au répertoire dans lequel vous souhaitez placer le code. 
Une fois que vous êtes dans le bon répertoire, vous devez exécuter la commande suivante :

`git clone https://github.com/rdcste/MF_stage`

Cela fera une copie locale de tous les fichiers pertinents.



### Environnement Python

Python permet aux utilisateurs de créer des environnements spécifiques adaptés à leurs applications.
Ces didacticiels inclus dans cette collection nécessitent un certain nombre de packages non standard. Dans ce répertoire, les utilisateurs trouveront un fichier *env_MF.yaml* qui pourra être utilisé pour
construire un environnement qui installera tous les packages requis.

Pour construire l'environnement, vous devez ouvrir un **terminal** (Linux/OSx) et accéder au dossier du référentiel que vous avez téléchargé dans la section **Installation** ci-dessus. Dans ce dossier se trouve un fichier appelé **env_MF.yml**. Celui-ci contient toutes les informations dont nous avons besoin pour installer les packages concernés.

Pour créer notre environnement Python, depuis le terminal (OSx/Linux), vous pouvez exécuter :
(Le gestionnaire de packages conda peut être lent)

`conda env create -f env_MF.yml `

Cela créera un environnement Python appelé *env_MF**. L'environnement ne sera pas activé par défaut. Pour l'activer, exécutez :

`conda activate env_MF`
et
`python -m ipykernel install --user –name=env_MF` (Utilisation de ce kernel dans le noteboook)

Maintenant, vous êtes prêt!

### Utiliser Jupyter Notebook

Ce module est basé sur une série de notebooks Jupyter. Ceux-ci prennent en charge un apprentissage interactif de haut niveau en nous permettant de combiner code, description textuelle et visualisations de données.
Pour exécuter Jupyter Notebook, ouvrez un terminal ou une invite de commande et assurez-vous d'avoir activé le bon environnement. Encore une fois, accédez au dossier du référentiel. Vous pouvez maintenant exécuter Jupyter en utilisant :
jupyter lab ou jupyter-lab, selon votre système d'exploitation.
Cela devrait ouvrir Jupyter Notebooks dans une fenêtre de navigateur.

Remarque:
Un répertoire MF_DATA contenant les fichiers sources est présent par défaut sur le JupyterHub mis à disposition
A défaut télécharger les données sur eumetsat.int

<hr>
<hr>
