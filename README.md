# Aurum — marketplace (version avancée)

Version avancée de la maquette de marketplace multi-vendeurs **Aurum** : pages HTML avec logique JavaScript modulaire (authentification, panier, favoris, commandes, factures, espace vendeur, administration) et données de démonstration.

## Structure

```
*.html               pages (accueil, catalogue, produit, panier, commande, vendeur, admin…)
assets/js/           app, auth, cart, order, invoice, product, seller, admin, data, utils
assets/css/          styles
docs/                guide marketplace, guide de modification, spécification backend, sécurité
```

La documentation détaillée est dans [`docs/`](docs/README.md), y compris la spécification de l'API et de la base de données prévues ([`docs/BACKEND_SPEC.md`](docs/BACKEND_SPEC.md)).

## Lancer

Ouvrir `index.html` dans un navigateur. Pour la vérification Playwright, voir [`README_PLAYWRIGHT.md`](README_PLAYWRIGHT.md).

> Licence : aucune licence n'est déclarée dans ce dépôt (tous droits réservés par défaut).
