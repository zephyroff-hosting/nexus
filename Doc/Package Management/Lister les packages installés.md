---
icon: /assets/icons/list-package.svg
order: 999
---
La solution propose une commande pour lister l'ensemble des packages installés sur un environnement.

```console
nxs list
```

La commande retournera une liste de package avec leur version.
<br>

#### Options

[!badge variant="info" text="-e"] ou [!badge variant="info" text="--env"] pour spécifier l'environnement<br>
[!badge variant="info" text="-r"] ou [!badge variant="info" text="--root"] pour afficher les environnements depuis l'environnement root<br>
[!badge variant="info" text="-o"] ou [!badge variant="info" text="--outdated"] pour afficher uniquement les packages qui ont une mise à jour disponible<br>
[!badge variant="info" text="-u"] ou [!badge variant="info" text="--upgradable"] pour afficher avec les mises à jour disponible<br>