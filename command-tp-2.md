### Création du dépôt sur github.`

```bash
git clone <adresse_depot>
```

1. intialisation
```bash
git add .
git commit -m "Initial commit with README.md and .gitignore"
git push origin main
```

2. Développement des fonctionnalités

- Gestion des articles
```bash
git checkout -b feature/gestion-articles
echo "Liste article \n -Titre : titre 1" > articles.txt
git add .
git commit -m "Ajout des articles"
echo "-Titre: titre 2" >> articles.txt
git commit -am "Ajout d'autres articles"
git push origin feature/gestion-articles
```
- Création du pull request, merge après validation

- Suppression de la branche feature/gestion-articles

```bash
git branch -d feature/gestion-articles
git push origin --delete feature/gestion-articles
```