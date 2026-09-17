# Lancement du projet mini-FPV drone

## 1. Mise en place du dépôt GitHub

### a. Lancement

L'intérêt d'un dépôt **Git** est de pouvoir réaliser un suivi des différentes versions de votre code, de sauvegarder au fur et à mesure votre progression, de revenir en arrière si besoin, etc.
**GitHub** propose l'hébergement de vos dépôts Git, ainsi que des services complémentaires de gestion de projet et d'automatisation des tâches.

1. Créez un compte GitHub si vous n'en possédez pas déjà un.
2. Créez un dépôt GitHub pour le projet.
3. Ajoutez tous les membres du groupe comme collaborateurs.
4. Ajoutez votre encadrant comme collaborateur : *charlypg* (La photo de profil est un chat façon Van Gogh).
5. Ajoutez un fichier `README.md` présentant brièvement :
   - les membres du groupe ;
   - l'objectif du projet ;
   - l'état d'avancement.

**Important :** Si Git et GitHub ne vous sont pas familiers, regardez des vidéos sur YouTube après avoir lu ce qui suit.

### b. Arborescence du dépôt

Nous sommes au lancement du projet. Il est donc normal que vous n'ayez qu'un README pour le moment et c'est très bien.
Sachez cependant que l'arborescence devrait au fur et à mesure de l'avancement du projet ressembler à cela :

```text
docs/
hardware/
├── schematics/
└── pcb/
firmware/
├── flight_controller/
└── transmitter/
tests/
README.md
```

Dans *docs/* se trouvera la documentation de votre projet et dans *tests/* les différents programmes de test.

### c. Liste non exhaustive de bonnes pratiques sur GitHub

- Les **commits** vous permettent de conserver les modifications de votre projet au fur et à mesure. Un commit a un titre. Il doit être **le plus clair et détaillé possible mais sans dépasser une ligne**. Ce titre doit dire ce qui a été modifié, comment et pourquoi. Lorsqu'il s'agit de code, privilégiez les petits commits aux gros commits. Il est alors plus facile de revenir en arrière ou d'identifier un bug.
- Les **branches** vous permettent de travailler sur des versions différentes de votre projet, de façon à ne pas se marcher sur les pieds, ou à détruire accidentellement un bloc de code fonctionnel. Une manière d'utiliser les branches, et pas la seule, est de créer une branche dès que vous voulez développer un nouveau module ou un nouvel aspect du projet. Par exemple, je sais que changer d'IMU peut bousculer l'ensemble du code, alors je créé une branche pour réaliser cette modification, et la tester, avant de l'intégrer.
- Utilisez les **Issues** pour répartir les tâches et signaler les bugs. **Attention :** Une tâche doit être précise. "Ajouter la fonction IMU", sans description, n'est pas une tâche. Le titre de la tâche doit être clair et la description d'un module doit spécifier au minimum les entrées, les sorties et leur type.
- Sur GitHub vous pouvez aussi créer un **projet** en plus du dépôt pour gérer les tâches ou l'emploi du temps (pas une obligation)
- **Utilisez les clés SSH !** C'est plus sécurisé et plus pratique. 

## 2. Points importants

- Identifier les risques techniques au fur et à mesure (masse et répartition, capacité et courant max batterie, ressources microcontôleur, etc). Vous pouvez créer un fichier *risks.md* dans votre dépôt pour lister ces risques. Identifiez les risques critiques qui peuvent paralyser le projet.
- Procéder de façon incrémentale. On intègre pas tout en même temps directement.
- Testez et validez les différents composants et modules au fur et à mesure.

