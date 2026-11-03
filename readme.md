# BeThom — Portfolio de graphiste freelance

## Présentation du projet

BeThom est un site vitrine fictif réalisé dans le cadre du Challenge 3 de la formation Product Builder.

L'objectif était d'intégrer les maquettes Figma desktop et mobile d'un portfolio pour Thomas, graphiste freelance spécialisé en identité visuelle, UI design et illustration.

Le site présente son profil, ses articles récents, ses projets et un formulaire de contact.

## Technologies utilisées

- **HTML5** : structure et contenu du site
- **CSS3** : mise en page, styles et responsive design
- **Flexbox et CSS Grid** : organisation des éléments
- **GitHub** : hébergement du code source
- **alwaysdata** : hébergement du site en ligne

Le projet ne nécessite aucun framework ni installation de dépendances.

## Typographie et identité visuelle

La police utilisée est **Heebo**, chargée via Google Fonts.

Couleurs principales :
- Bleu marine : `#21243D`
- Corail : `#FF6464`
- Bleu clair : `#EDF7FA`
- Blanc : `#FFFFFF`

## Fonctionnalités

- Navigation par ancres vers les différentes sections
- Header sticky
- Menu hamburger sur mobile
- Présentation des articles et des réalisations
- Formulaire de contact (interface de démonstration)
- Téléchargement d'un PDF de démonstration
- Affichage responsive desktop et mobile
- Métadonnées SEO et favicon
- Attributs `alt` pour les images et labels pour les champs du formulaire

## Installation en local

1. Cloner le dépôt :

   `git clone https://github.com/mathilde-lmnz/workshp3-portefolio.git`

2. Ouvrir le dossier `workshp3-portefolio` dans VS Code.

3. Ouvrir le fichier `index.html` dans un navigateur ou utiliser l'extension **Live Server** de VS Code.

Aucune installation supplémentaire n'est nécessaire.

## Structure du projet

```text
workshp3-portefolio/
├── index.html
├── styles/
│   └── style.css
├── assets/
│   ├── images et icônes
│   └── cv-thomas.pdf
└── README.md
```

## Validation et accessibilité

Le code HTML a été contrôlé avec le validateur W3C : aucune erreur ni aucun avertissement signalé.

La structure comprend un H1 unique, une hiérarchie de titres H2/H3, des images avec attributs `alt`, des labels associés aux champs du formulaire et une déclaration de langue `lang="fr"`.

**Point d'attention :** le bouton principal présente un contraste de 2,89:1, inférieur au seuil WCAG AA de 4,5:1 pour du texte normal. Le choix a été fait de conserver les couleurs de la maquette originale.

Une différence typographique a également été relevée dans la maquette Figma. La police Heebo a été conservée sur l'ensemble du site pour assurer la cohérence graphique.

## Liens du projet

- **Site en ligne :** https://mathildelmnz.alwaysdata.net/
- **Dépôt GitHub :** https://github.com/mathilde-lmnz/workshp3-portefolio

## Contexte

Projet pédagogique réalisé à partir d'une maquette Figma fournie dans le cadre du Challenge 3.

Le contenu présenté est fictif.
