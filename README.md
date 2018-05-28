# Base projet angular pour les exercices de cours

Cette base est destinée aux élèves des cours de d'AngularJs pour s'en servir comme base pour les exercices.

## Lancer le serveur web 

Avant tout de chose, vérifiez que vous avez NodeJs d'installé.
Pour cela, allez dans votre terminal (Git bash ou powershell), et tapez la commande suivante:

``` bash

node -v

```

Si le retour indique "Command not found", c'est que node JS n'est pas installé, sinon le message affiché sera de ce genre: `v9.3.0`.
Si vous n'avez pas NodeJs installé sur votre ordinateur, rendez vous à cette [adresse](https://nodejs.org/en/) et cliquez sur le bouton "current".

Ceci va lancer le téléchargement d'un exécutable, vous aurez juste à l'installer et à suivre les instructions.
Fermez et relancez votre terminal et la version devrait s'afficher maintenant.

Une fois que vous avez NodeJs qui fonctionne, ouvrez un terminal dans ce dossier, où rendez vous dans le dossier à l'aide de la commande `cd`

Une fois dans le dossier, lancez la commande `npm install`.
Vous devriez avoir un téléchargement qui se lance dans votre terminal.

Une fois terminé, lancez la commande `npm start`.

Vous devriez avoir afficher ceci:
``` bash
> angular1.6-base@1.0.0 start /home/kristen-linux/Documents/Kristen/Projects/angular1.6-base
> httpster

Starting HTTPster v1.0.3 on port 3333 from /home/kristen-linux/Documents/Kristen/Projects/angular1.6-base
```

Si cela s'affiche, rendez vous à cette adresse [http://localhost:3333](http://localhost:3333)
Vous devriez avoir votre application qui s'affiche.

Vous pouvez désormais développer sans vous soucier du problème de fichier.

Si vous rencontrez un problème n'hésitez pas à me contacter.