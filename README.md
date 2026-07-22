# arab-ait-taleb-Rattrapage-ue04
# UE04 - Forge ton code : Reproduction de la page "Histoire HETIC"

## Sujet du projet

Ce projet consiste à reproduire fidèlement la page **"Histoire HETIC"** du site officiel de l'école HETIC (https://www.hetic.net/ecole-tech-web-et-numerique/histoire-hetic), en respectant :
- la structure générale de la page,
- les sections principales (header, hero, contenu, actualités, candidature, footer),
- la hiérarchie visuelle,
- le responsive desktop et mobile.

Ce projet a été réalisé dans le cadre du rattrapage de l'UE04 "Forge ton code".

##  Technologies utilisées

- **HTML5** (sémantique)
- **CSS3** (variables CSS, Flexbox, CSS Grid, colonnes CSS pour la mise en page type "journal")
- **JavaScript** (vanilla JS pour le menu burger mobile et l'effet de scroll du header)

##  Organisation des fichiers
Rattrapage-ue04/
│
├── index.html
├── README.md
│
├── assets/
│ └── images/
│
├── css/
│ └── style.css
│
└── js/
└── main.js

- `index.html` : structure de la page (header, hero, contenu, actualités, candidature, blocs de liens, footer)
- `css/style.css` : ensemble des styles, organisés par section, avec media queries pour le responsive
- `js/main.js` : gestion du menu burger mobile et de l'effet de scroll sur le header
- `assets/images/` : toutes les images utilisées dans la page

##  Comment lancer le projet

1. Cloner le repository :
```bash
   git clone https://github.com/AitTalebArab/Rattrapage-ue04.git
```
2. Ouvrir le dossier dans un éditeur de code (VS Code par exemple)
3. Ouvrir le fichier `index.html` directement dans un navigateur

Aucune installation ni dépendance n'est nécessaire : le projet est en HTML/CSS/JS natif.

##  Ce qui a été réalisé

- Structure HTML sémantique complète de la page
- Reproduction du header avec navigation, mega-menu et version mobile dédiée
- Reproduction de la hero section, de l'intro et du contenu principal en deux colonnes
- Section actualités avec cartes
- Section candidature et blocs de liens
- Footer complet avec bloc contact, liens rapides et certification Qualiopi
- Menu burger fonctionnel en JavaScript
- Effet de scroll sur le header (transparent → blanc)
- Responsive desktop et mobile

##  Difficultés rencontrées

-Un peu pour la responsive parce que y a pas mal de changement par rapport au desktop

##  Améliorations possibles

- Rendre le mega-menu accessible au clavier (navigation via Tab)
- Ajouter des animations et transitions plus poussées
- Optimiser le chargement des images (lazy loading, formats WebP systématiques)

##  Auteur

- Nom / Prénom : Arab AIT TALEB

