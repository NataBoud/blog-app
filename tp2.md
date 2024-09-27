### Sujet de TP : Utilisation du GitHub Flow pour le Développement d'une Application de Blog

#### **Contexte :**
Vous faites partie d'une équipe de développement travaillant sur une application de blog. L'objectif est de mettre en place des fonctionnalités de gestion des articles, des commentaires et des utilisateurs en utilisant le workflow **GitHub Flow**. Vous allez créer et gérer des branches de fonctionnalités, soumettre des pull requests, et fusionner les modifications dans la branche principale (`main`).

#### **Objectifs :**
- Appliquer le workflow GitHub Flow pour le développement de nouvelles fonctionnalités.
- Apprendre à créer des branches de fonctionnalité à partir de `main`.
- Savoir soumettre des pull requests pour valider le code.
- Gérer les fusions dans la branche `main` et simuler le processus de déploiement.

#### **Travail à Réaliser :**

1. **Initialisation du Projet :**
   - Créez un nouveau dépôt GitHub nommé `blog-app`.

2. **Développement des Fonctionnalités :**
   Vous allez développer trois fonctionnalités principales. Pour chaque fonctionnalité :
   - Créez une branche à partir de `main`.
   - Ajoutez des fichiers ou des commentaires pour simuler le développement.
   - Effectuez plusieurs commits pour représenter l'évolution de la fonctionnalité.

   **Fonctionnalités à développer :**
   - **Fonctionnalité 1 : Gestion des Articles**
     - Implémentez la possibilité d'ajouter, modifier et supprimer des articles de blog.
     - Fichiers simulés : `articles.txt` pour lister les articles.
   - **Fonctionnalité 2 : Gestion des Commentaires**
     - Ajoutez une fonctionnalité permettant aux utilisateurs de commenter les articles.
     - Fichiers simulés : `comments.txt` pour lister les commentaires par article.
   - **Fonctionnalité 3 : Gestion des Utilisateurs**
     - Implémentez la possibilité d'enregistrer de nouveaux utilisateurs et de se connecter.
     - Fichiers simulés : `users.txt` pour lister les utilisateurs.

3. **Création de Pull Requests :**
   - Pour chaque branche `feature`, ouvrez une pull request (PR) sur GitHub vers la branche `main`.
   - Ajoutez une description détaillée de la fonctionnalité dans la PR.
   - Simulez une revue de code en laissant des commentaires sur la PR.

4. **Fusion des Fonctionnalités dans `main` :**
   - Après approbation de chaque pull request, fusionnez la branche de fonctionnalité dans `main`.
   - Supprimez la branche de fonctionnalité après la fusion.

5. **Simulation de Bug et Correction :**
   - Ajoutez un fichier `bug_report.md` à la racine du projet pour décrire un bug fictif, par exemple, "Les utilisateurs ne peuvent pas commenter un article".
   - Créez une branche à partir de `main` pour corriger ce bug.
   - Apportez les modifications nécessaires dans un fichier de simulation (`comments.txt`).
   - Ouvrez une pull request pour cette correction et fusionnez-la dans `main` après validation.

6. **Déploiement Simulé :**
   - Après avoir fusionné toutes les fonctionnalités, ajoutez un fichier `DEPLOYMENT.md` qui décrit le processus de déploiement fictif
