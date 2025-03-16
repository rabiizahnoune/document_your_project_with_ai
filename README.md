# Générateur de Structure de Projet

Ce projet contient un script Python simple mais puissant qui permet de générer automatiquement un fichier texte contenant la structure d’un projet (dossiers et fichiers) ainsi que le contenu des fichiers texte. L’objectif ? Faciliter la documentation de vos projets en fournissant une base que vous pouvez ensuite utiliser manuellement ou envoyer à un modèle de langage (LLM) pour générer une documentation complète.

## Fonctionnalités
- Parcours récursif de tous les dossiers et fichiers d’un répertoire.
- Exclusion automatique des dossiers inutiles (ex. `.git`, `node_modules`).
- Extraction du contenu des fichiers texte (UTF-8).
- Génération d’un fichier `project_structure.txt` structuré et lisible.

## Utilisation
1. **Prérequis** : Assurez-vous d’avoir Python installé (version 3.x recommandée).
2. **Téléchargement** : Clonez ce dépôt ou téléchargez le fichier `generate_structure.py`.
3. **Exécution** :
   - Placez le script dans le répertoire racine de votre projet (ou modifiez `project_path` dans le code pour pointer vers votre projet).
   - Exécutez le script avec :
     ```bash
     python doc.py
