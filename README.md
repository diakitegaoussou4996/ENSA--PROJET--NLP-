
# Reconnaissance d'Entités Nommées avec Embeddings GloVe et LSTM

Ce projet se concentre sur la détection d'entités nommées en utilisant des embeddings GloVe pré-entraînés et un réseau de neurones récurrent (LSTM) bidirectionnel. La reconnaissance d'entités nommées est une tâche clé en traitement automatique du langage naturel (NLP), qui consiste à identifier et classifier les entités telles que les personnes, les lieux, les organisations, etc., dans un texte.

## Données Utilisées :
Le projet utilise le jeu de données CONLL 2003, qui est largement utilisé dans la recherche en NLP pour la reconnaissance d'entités nommées. Ce jeu de données contient des articles de presse en anglais annotés avec les entités nommées suivantes : personnes (PER), lieux (LOC), organisations (ORG) et autres entités diverses (MISC). Les données sont réparties en ensembles d'entraînement, de validation et de test, avec des annotations fournies pour chaque mot dans le texte.

## Fonctionnalités principales :
- Utilisation des embeddings GloVe pour capturer les informations sémantiques des mots.
- Implémentation d'un LSTM bidirectionnel pour la modélisation séquentielle.
- Utilisation d'un jeu de données annotées pour l'entraînement et l'évaluation du modèle.
- Évaluation des performances du modèle en termes de précision, rappel et score F1 pour chaque classe d'entité nommée.
- Utilisation de techniques telles que le callback EarlyStopping pour éviter le surapprentissage.

## Contenu du Projet :
- Scripts Python pour le prétraitement des données, la construction du modèle, l'entraînement et l'évaluation.
- Fichiers de configuration pour l'optimisation des hyperparamètres et la gestion des callbacks.
- Notebooks Jupyter pour l'analyse exploratoire des données et la visualisation des résultats.
- Documentation détaillée sur l'architecture du modèle, les algorithmes utilisés et les résultats obtenus.
- Instructions pour la reproduction des résultats et l'utilisation du modèle dans d'autres projets.

Ce projet est une démonstration de l'application des techniques modernes de NLP pour résoudre des problèmes concrets, avec un accent particulier sur la reconnaissance précise des entités nommées dans les textes.

