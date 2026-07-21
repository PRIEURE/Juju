# Road Trip Bordeaux → Espagne (4 jours)

Site statique du carnet de route, une page par jour.

## Publier sur GitHub Pages

1. Va sur https://github.com/new et crée un nouveau repository (par ex. `roadtrip-espagne`), en public.
2. Sur ta machine, dans le dossier de ce site :
   ```bash
   git init
   git add .
   git commit -m "Roadtrip Bordeaux → Espagne"
   git branch -M main
   git remote add origin https://github.com/<ton-pseudo>/roadtrip-espagne.git
   git push -u origin main
   ```
3. Sur GitHub : **Settings → Pages → Source → Deploy from a branch → main / (root)** → **Save**.
4. Après 1-2 minutes, le site est en ligne à l'adresse :
   `https://<ton-pseudo>.github.io/roadtrip-espagne/`

## Structure

- `index.html` — vue d'ensemble des 4 jours
- `jour-1.html` à `jour-4.html` — une page par jour (trajet, étapes, restaurant du soir)
- `style.css` — feuille de style partagée

## Mise à jour
Contient maintenant : page d'accueil avec photo de couverture, Jour 1-4 avec le programme complet (dont l'anniversaire fêté le soir du Jour 3 à San Sebastián), et une page Technique regroupant toutes les adresses avec liens Waze directs + l'appli Park4Night pour le van.
