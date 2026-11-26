# Orbital Fleet — mise en ligne sur GitHub Pages

Ce dossier est prêt à l'emploi : rien à modifier, rien à compiler.

```
index.html      page du site
app.js          code (Three.js inclus)
models/         les 5 modèles 3D (.glb)
.nojekyll       dit à GitHub de servir les fichiers tels quels
```

## Étapes (≈ 3 minutes)

1. Sur github.com, crée un dépôt (bouton **New**). Nom au choix, par exemple `orbital-fleet`. Mets-le en **Public**.
2. Dans le dépôt vide, clique **uploading an existing file**.
3. **Ouvre ce dossier, sélectionne tout son contenu** (index.html, app.js, le dossier models, .nojekyll) et glisse-le dans la page GitHub.
   Important : glisse le *contenu*, pas le dossier parent, pour que `index.html` soit à la racine du dépôt.
   (Si .nojekyll n'est pas visible sur ton PC, ce n'est pas grave : le site fonctionne sans.)
4. Attends la fin du transfert, puis clique **Commit changes**.
5. Va dans **Settings → Pages**. Sous *Build and deployment*, choisis **Deploy from a branch**, branche **main**, dossier **/ (root)**, puis **Save**.
6. Après 1 à 2 minutes, le site est en ligne à l'adresse :
   `https://TON-PSEUDO.github.io/orbital-fleet/`

## Conseils
- Si tu vois une page 404, attends encore une minute et vérifie que `index.html` est bien à la racine du dépôt.
- Pour mettre à jour le site plus tard : refais un glisser-déposer des fichiers modifiés dans le dépôt (Add file → Upload files).
- Le son démarre au premier clic ou toucher (règle des navigateurs). Le bouton « SON » en haut à droite le coupe.
- Modèles 3D : vérifie la licence de chaque auteur (CC-BY demande de les citer) avant une diffusion publique.
