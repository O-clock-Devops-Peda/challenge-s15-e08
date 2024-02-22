# challenge-s15-e08
External Values


## Modifiez votre app.py
Modifiez votre app.py afin d'afficher le contenu d'une variable d'environnement de votre choix.

## Modifiez votre chart
Chargez cette variable avec un nouveau configmap (vous devez donc avoir 2 configmap dans le front).

## Créez 2 repos git: prod et dev
créez un repo prod qui contiendra votre fichier values de prod et un fichier values de dev

## Créez deux applications une pour la prod une pour la dev
Vos deux applications devront afficher leurs propres variables.
Ces applications seront créées à l'aide des objets CRD Application.
Si vous reprenez votre chart Helm iaac, elle contiendra alors 1 objet projet et 2 objets application (attention à bien specifier un nom d'application pour chaque contrairement à la doc suivante).
En suivant:
https://argo-cd.readthedocs.io/en/stable/user-guide/multiple_sources/#helm-value-files-from-external-git-repository



