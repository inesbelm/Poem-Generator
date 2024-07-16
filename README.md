# Générateur de Poèmes

Ce projet, issu de ma passion personnelle pour la poésie, est un générateur de poèmes automatisé. Il utilise des techniques avancées de traitement du langage naturel pour créer des poèmes, en s'inspirant de divers styles et thèmes.

## Installation

Assurez-vous d'avoir Python 3 installé sur votre système pour exécuter ce projet.

### Dépendances

Pour installer les bibliothèques nécessaires, exécutez le code suivant :
pip install -q kaggle
pip install --upgrade --force-reinstall --no-deps kaggle


### Configuration

1. **Clé API Kaggle** : Avant de télécharger les données nécessaires, configurez votre clé API Kaggle. Téléchargez votre `kaggle.json` depuis votre compte Kaggle et chargez-le dans l'environnement d'exécution avec ce code :

from google.colab import files
files.upload()


2. **Téléchargement des données** : Utilisez les commandes intégrées au notebook pour télécharger le dataset des poèmes depuis Kaggle.

## Utilisation

Lancez le notebook pour générer un poème. Le système vous proposera de choisir un style ou un thème pour personnaliser le poème généré.

## Technologies

- Python 3
- API Kaggle
- Traitement du langage naturel

## Contribution

Les suggestions et contributions pour améliorer ce projet sont toujours bienvenues. N'hésitez pas à soumettre vos idées ou modifications via une pull request.

## Licence

Distribué sous la licence MIT, ce projet est libre d'utilisation pour tous. Consultez le fichier `LICENSE` pour plus de détails.
