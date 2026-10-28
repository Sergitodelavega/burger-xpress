# Burger Xpress

Site vitrine responsive pour Burger Xpress, une marque de burgers. La page présente le burger vedette, la carte, les avis clients et une inscription à la newsletter. Elle est construite en HTML et CSS généré avec Tailwind CSS.

## Démarrage rapide

Prérequis : Node.js et npm.

```bash
npm ci
npm run dev
```

`npm run dev` surveille `src/input.css` et régénère `public/style.css` à chaque modification. Dans un second terminal, servez le dossier `public` avec un serveur HTTP statique, par exemple :

```bash
python3 -m http.server 8000 --directory public
```

Ouvrez ensuite [http://localhost:8000](http://localhost:8000). Pour un aperçu simple sans serveur, ouvrez `public/index.html` directement dans votre navigateur.

## Structure

- `public/index.html` — contenu et structure de la page.
- `public/style.css` — feuille de style compilée, chargée par le site.
- `public/images/` — logos, photos des burgers et portraits.
- `src/input.css` — styles source et règles responsive.
- `tailwind.config.js` — configuration Tailwind CSS.

## Fonctionnalités

- Navigation par ancres vers les sections de la page.
- Présentation responsive des burgers, avis clients et formulaire newsletter.
- Styles adaptés aux petits écrans et prise en compte de la préférence de réduction des animations.

Le formulaire newsletter est une interface statique : aucun service d’inscription n’est actuellement connecté.
