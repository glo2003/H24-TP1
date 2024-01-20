[← Back](../README.md)

# Clean Code

Votre code doit suivre les meilleures pratiques de Clean Code telles que décrites dans le livre de Robert C. Martin. Plus particulièrement, votre code doit :

- Être lisible
- Avoir de l'espace vertical adéquat
- Avoir de l'espace horizontal adéquat
- Avoir des noms de variables, de fonctions et de classes claires et représentatives
- Avoir des fonctions de taille acceptable

Pour vous aider, on vous oblige à mettre en place un outil d'analyse de formatage.

## Analyse de formatage

Vous devez installer un plugin Maven permettant d'analyser le formatage de votre code. Vous devez **fournir la commande** (_goal_ Maven) permettant d'effectuer la vérification dans le fichier d'exercice. Votre plugin peut également offrir la possibilité de faire du formatage automatique. Dans tous les cas, assurez-vous que le code remis soit bien formatté selon votre outil! Vous devrez également l'adapter à votre projet, c'est-à-dire le configurer selon votre style voulu et seulement pour les fichiers désirés (ex: pas besoin de configuration pour les fichiers OCaml...).

Voici quelques exemples d'outils offerts sur Maven :

- Checkstyle
- Spotless
- Prettier
- EditorConfig

Vous êtes invités à essayer et comparer les différents outils afin de choisir celui qui vous convient le mieux.
