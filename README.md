### Sujet de TP : Utilisation du GitHub Flow pour le Développement d'une Application de Blog

#### **Objectifs :**
- Appliquer le workflow GitHub Flow pour le développement de nouvelles fonctionnalités.
- Apprendre à créer des branches de fonctionnalité à partir de `main`.
- Savoir soumettre des pull requests pour valider le code.
- Gérer les fusions dans la branche `main` et simuler le processus de déploiement.

1. **Développement des Fonctionnalités :**
   Développer trois fonctionnalités principales : Gestion des Articles, Gestion des Commentaires, Gestion des Utilisateurs. 
   
   Pour chaque fonctionnalité. Créez une branche à partir de `main`:
    -  **'feature/gestion-des-articles'**

    ````bash
    git checkout -b feature/gestion-des-articles
    ````
    Ajout des fonctionnalités
    ````bash
    git switch main
    ````
    -  **'feature/gestion-des-commentaires'**

    ````bash
    git checkout -b feature/gestion-des-commentaires
    ````
    Ajout des fonctionnalités

    ````bash
    git switch main
    ````
    -  **'feature/gestion-des-utilisateurs'**

    ````bash
    git checkout -b feature/gestion-des-utilisateurs
    ````
    Ajout des fonctionnalités

    ````bash
    git switch main
    ````

2. **Création de Pull Requests :**
   - Pour chaque branche `feature`, ouvrir une pull request (PR) sur GitHub vers la branche `main`.

3. **Fusion des Fonctionnalités dans `main` :**
Example : 

    ````bash
    git merge origin/feature/gestion-des-commentaires
    ````

4. **Simulation de Bug et Correction :**
   - Ajoutez un fichier `bug_report.md` à la racine du projet pour décrire un bug fictif, par exemple, "Les utilisateurs ne peuvent pas commenter un article".
   - Créez une branche à partir de `main` pour corriger ce bug.
   - Apportez les modifications nécessaires dans un fichier de simulation (`comments.txt`).
   - Ouvrez une pull request pour cette correction et fusionnez-la dans `main` après validation. 
   

5. **Déploiement Simulé :**
- Après avoir fusionné toutes les fonctionnalités, ajoute un fichier `DEPLOYMENT.md` qui décrit le processus de déploiement fictif
