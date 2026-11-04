# pathmnist-deep-learning-project

Ce projet de Deep Learning implémente un Réseau de Neurones Convolutif (CNN) de zéro pour classifier des images d'histopathologie du dataset **PathMNIST** (MedMNIST), qui contient 9 classes de tissus différents.

## Fonctionnalités du projet
- Utilisation de **PyTorch** pour la construction et l'entraînement du CNN.
- Application de **Data Augmentation** pour améliorer la robustesse du modèle.
- Intégration d'une régularisation L2 (**Weight Decay**) et d'un **Learning Rate Scheduler** (ReduceLRonPlateau) pour stabiliser l'apprentissage.
- Évaluation complète via une **Matrice de Confusion** et un **Rapport de Classification**.

## Résultats
- Précision globale (*Accuracy*) sur le jeu de test : **~86% - 92%**
