#Projet de Classification des Chiffres Manuscrits avec CNN

Ce projet implémente un réseau de neurones convolutionnel (CNN) pour classer les chiffres manuscrits à partir de l'ensemble de données MNIST. L'objectif est d'appliquer un modèle d'apprentissage supervisé pour reconnaître les chiffres manuscrits de manière efficace en utilisant des techniques de deep learning.

Étapes du projet :
1.Prétraitement des données : Nettoyage des images (redimensionnement, normalisation) pour les rendre adaptées à l'entraînement du modèle.
2.Séparation des données : Division de l'ensemble de données en ensembles d'entraînement, de validation et de test.
3.Conception du modèle CNN : Construction d'un modèle de réseau de neurones convolutionnels avec plusieurs couches pour extraire des caractéristiques importantes des images.
4.Compilation et entraînement : Utilisation de TensorFlow et Keras pour compiler et entraîner le modèle sur les données d'entraînement.
5.Évaluation des performances : Évaluation du modèle sur l'ensemble de test à l'aide de métriques de classification (précision, recall, etc.).

Technologies utilisées :
Python : Langage de programmation principal.
TensorFlow, Keras : Bibliothèques pour construire et entraîner les réseaux de neurones.
Scikit-learn : Utilisé pour certaines étapes de prétraitement et évaluation.
NumPy, Pandas : Utilisés pour le traitement des données et la gestion des tableaux.
