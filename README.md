# Garage Auto Repair — Site vitrine

Site multipage réalisé en HTML5, CSS3 et JavaScript Vanilla.

## Lancer le site

1. Décompressez le dossier.
2. Ouvrez `index.html` dans un navigateur, ou utilisez l'extension Live Server de Visual Studio Code.
3. Les pages secondaires se trouvent dans `pages/`.

## Architecture

- `index.html` : accueil
- `pages/about.html` : à propos
- `pages/services.html` : prestations
- `pages/specialites.html` : spécialités
- `pages/galerie.html` : galerie et agrandissement des visuels
- `pages/faq.html` : questions fréquentes interactives
- `pages/contact.html` : formulaire de demande
- `css/style.css` et `css/responsive.css` : styles
- `js/main.js` : navigation, FAQ, lightbox et validation du formulaire
- `js/config.js` : coordonnées et configuration de l'envoi
- `assets/images/` : visuel local du projet

## Personnalisation indispensable avant publication

Modifier `js/config.js` et renseigner les informations officielles : téléphone, WhatsApp, e-mail, adresse, ville et horaires. Ajouter également le logo réel, la présentation validée et la liste exacte des prestations proposées.

Le formulaire est validé côté navigateur. **Il ne transmet aucune demande tant qu'un endpoint de formulaire n'est pas configuré** dans `formEndpoint` de `js/config.js`. Le code prévoit l'envoi JSON vers cet endpoint et n'affiche un succès qu'après une réponse HTTP positive.

Les prestations et domaines d'intervention sont repris du cahier des charges et doivent être validés par l'entreprise. Aucun label, agrément, certification, partenariat, marque partenaire, tarif ou garantie n'est revendiqué.

## Images

Le visuel local fourni dans `assets/images/atelier-diagnostic.png` est une image d'illustration générée pour cette maquette. Remplacez-le par des photographies réelles de l'atelier, des mécaniciens et des interventions avant publication. La galerie signale explicitement ce caractère provisoire.

## SEO

Chaque page possède un titre, une description meta, une structure sémantique et des textes alternatifs d'images. Le référencement local sera à compléter avec la ville et l'adresse exactes.
