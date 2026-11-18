# Appli-web — Interface du site Sneakers Store

Pages HTML, CSS et JavaScript de l'interface de **SkStore**, une boutique de sneakers en ligne. Ces pages sont les gabarits utilisés par le site Django [Skstore](https://github.com/EdNganji/Skstore).

## Pages

| Fichier | Contenu |
|---|---|
| `index.html` | Accueil : bannière, marques, dernières sorties, infolettre |
| `showcase.html` | Vitrine de tous les articles |
| `product.html` | Fiche détaillée d'un produit |
| `base.html` | Gabarit commun (en-tête, pied de page) |
| `save.html` | Page de sauvegarde |

## Technologies

- HTML5, CSS3
- Bootstrap 4, jQuery
- Owl Carousel, Slick, Lightbox, ScrollReveal

## Structure

```
ressources/
├── css/      # Bootstrap, styles du site
├── js/       # jQuery et plugins
└── images/   # Images des produits et logo
```

## Aperçu

Ouvrir `index.html` dans un navigateur.

> Les pages contiennent des balises de gabarit Django (`{{ brand.0.name }}`, etc.) : elles s'affichent pleinement une fois servies par l'application [Skstore](https://github.com/EdNganji/Skstore).

## Auteur

**Daniel Nganjip** — projet réalisé en 2023.
