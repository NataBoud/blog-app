### Description

- Un workflow simplifié pour les déploiements continus.

##### Branches princpales

- **main**: Branche principale ou le code est déployé.
- **Branches de fonctionnalités**: Créées à partir du main pour développer de nouvelles fonctionnalités. La fusion se fait après validation (pull request).
- **Etapes:**
    1. Créer une branche pour une fonctionnalité ou un bug.
    2. Développer la fonctionnalité et la tester.
    3. Créer une pull request pour examiner le code.
    4. Fusionner la branche des main après validation.
    5. Déployer.
- **Avantage**: Simple, favorise les déploiments rapides.
- **Inconvénients**: Moins structuré, difficile à gérer pour les grands projets

![Github Workflow](./images/github.png)