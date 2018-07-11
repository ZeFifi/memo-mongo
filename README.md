# Memo Mongo

Ce repo répertorie tous les points importants relatif à l'apprentissage de MongoDB.

*Disclaimer : Étant sous Mac OS, je ne traiterai ici que des spécificités de ce système d'exploitation. Néanmoins, toutes les démarches devraient être identiques pour tous les OS, à l'exception de l'installation.*

# Qu'est-ce que MongoDB ?



# Installation de MongoDB sous Mac OS

Pour faciliter les choses, il faut au préalable installer Homebrew. Pour cela, [rendez-vous ici](https://brew.sh/index_fr) et suivez les instructions.

Pour vérifier que l'installation s'est bien déroulée, tapez `brew -v`. Le terminal vous donnera alors la version actuellement installée sur votre OS.

Ensuite, exécutez les commandes suivantes pour installer MongoDB : `brew update` puis `brew install mongodb`.

Ici aussi, pour vérifier que l'installation s'est bien déroulée, faites `mongod --version`.

Maintenant que tout est OK pour l'installation, passons à l'étape suivante.

# Créer une base de données

Pour créer une base de données, lancez tout d'abord le Mongo Daemon en tapant `mongod` dans le répertoire de votre projet, puis `mongo`. Ensuite, tapez la commande `use` suivi du nom de la base de données choisi :

```use memoMongo```