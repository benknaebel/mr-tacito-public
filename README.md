# Mr Tacito : fichiers publics

Ce dépôt contient seulement ce que le programme Mr Tacito lit en ligne :

- `conditions.json` : l'avertissement et les mentions légales en vigueur, signés par l'éditeur. Le programme les lit au démarrage et vérifie la signature. Si la version est plus récente que celle acceptée, il la présente de nouveau à l'utilisateur.

Le code du programme n'est pas ici. Ne modifiez pas `conditions.json` à la main : la signature ne correspondrait plus et le programme l'ignorerait. Passez par `npm run conditions -- publier` dans le dépôt du programme.
