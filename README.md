# Portfolio — Shubham Sharma

Portfolio one-page, simple, moderne et responsive, généré à partir de l'analyse du profil
LinkedIn (`linkedin.com/in/sharmashubham1`) et de la chaîne YouTube (`@shubham_sharma`).

Aucun framework : HTML/CSS/JS pur, pour un déploiement immédiat (GitHub Pages, Netlify,
Vercel, ou simplement en ouvrant `index.html`).

## Structure

```
index.html        page unique (hero, à propos, parcours, compétences, projets, YouTube,
                   témoignage, contact, footer)
css/style.css      styles, variables de thème (couleurs/rayons) en haut du fichier
js/script.js       menu mobile, thème clair/sombre, animations au scroll, compteurs,
                   formulaire de contact (démo front-end)
```

## Personnaliser rapidement

- **Couleurs / thème** : modifier les variables CSS en haut de `css/style.css`
  (`--accent`, `--accent-2`, `--radius-*`...).
- **Textes** : tout le contenu est directement dans `index.html`, section par section.
- **Photo** : le hero et la section YouTube utilisent des placeholders graphiques
  (dégradés/icônes) plutôt qu'une vraie photo — à remplacer par une image réelle si besoin.
- **Email de contact** : `mailto:contact@votre-domaine.fr` dans la section `#contact`
  est un placeholder à remplacer par une vraie adresse.
- **Formulaire de contact** : fonctionne en démo (affiche juste un message de confirmation).
  Pour le rendre réellement fonctionnel, le brancher à un service comme Formspree,
  EmailJS ou Netlify Forms.

## Notes sur les informations utilisées et hypothèses

LinkedIn bloque le scraping automatisé (profil non accessible directement) et la page
YouTube est fortement dynamique (JS), donc le contenu a été reconstitué à partir de
recherches web publiques (articles, interviews, podcasts, site personnel). Points à
vérifier/ajuster :

- **Chiffres clés** (abonnés YouTube ~300k, newsletter ~52k, 830+ entreprises, 500+ vidéos)
  proviennent de sources publiques trouvées en ligne et peuvent avoir évolué depuis —
  à mettre à jour avec les chiffres réels et à jour.
- **Parcours professionnel** (EPITA 2015, Mailjet, Keymetrics, Qonto) reconstitué à partir
  d'articles et d'interviews publics — dates et intitulés de poste à confirmer/ajuster.
- **Témoignage client** repris d'un cas cité publiquement — à remplacer par de vrais
  témoignages si disponibles.
- **Logos "Ils me font confiance"** (Notion, Qonto, Make, n8n, Hostinger, Pennylane) sont
  affichés en texte ; à remplacer par de vrais logos avec autorisation si besoin.
- **Email de contact** est un placeholder à personnaliser.

Ces hypothèses sont clairement identifiables dans le code et peuvent être corrigées
directement dans `index.html`.
