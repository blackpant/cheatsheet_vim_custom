# Vim Cheatsheet — spécial commandes `g`

Aide-mémoire visuel des commandes Vim les plus utiles, avec une section entière consacrée au préfixe `g` (le plus riche et le plus sous-exploité de Vim) et à la commande `:g` (global).

**Démo en ligne :** https://vim-cheatsheet-heisecloud.vercel.app

## Contenu

- Déplacements de base (`hjkl`, `w`/`b`/`e`, `0`/`^`/`$`, `{`/`}`, `%`...)
- **Le préfixe `g` en entier**, organisé par catégorie :
  - navigation dans le buffer (`gg`, `G`, `ge`, `gd`, `gf`...)
  - déplacement par ligne d'écran / wrap (`gj`, `gk`, `g0`, `g$`...)
  - changement de casse (`gu`, `gU`, `g~`, `guu`, `gUU`...)
  - formatage et jointure (`gq`, `gw`, `gJ`)
  - édition, historique et recherche (`gv`, `gi`, `g;`, `g&`, `g*`...)
  - onglets et fenêtres (`gt`, `gT`)
- **La commande `:g` (global)** : anatomie `:g/motif/commande` et exemples courants (`:g/TODO/d`, `:g/pattern/t$`, `:g/pattern/normal A;`...)
- Édition, recherche & remplacement, mode visuel, fenêtres & buffers

## Aperçu

Page HTML autonome (aucune dépendance de build), thème sombre inspiré de la palette [Gruvbox](https://github.com/morhetz/gruvbox), avec une variante claire automatique selon les préférences système.

## Utilisation

Ouvrir simplement `index.html` dans un navigateur — aucune installation requise.

```bash
open index.html        # macOS
xdg-open index.html    # Linux
```

## Déploiement

Le site est déployé sur [Vercel](https://vercel.com), avec déploiement automatique à chaque push sur la branche principale.

## Stack

- HTML/CSS pur, un seul fichier
- Polices [JetBrains Mono](https://www.jetbrains.com/lp/mono/) et [Inter](https://rsms.me/inter/) via Google Fonts

## Licence

Libre d'utilisation et de modification.
