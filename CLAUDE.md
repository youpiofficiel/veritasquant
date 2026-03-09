# Veritas Quant — Site vitrine

## Structure
- `index.html` — Landing page EN (hero full-screen, datum cards, data band)
- `approach.html` — Méthodologie EN (Gate 1/Gate 2 cards, deliverables dark block)
- `services.html` — Services EN (Mode A/B cards, 4 engagement cards 2×2, process cards)
- `team.html` — Équipe EN (3 membres, confidentiality block)
- `contact.html` — Formulaire de contact EN
- `index-fr.html`, `approach-fr.html`, `services-fr.html`, `team-fr.html`, `contact-fr.html` — Pages FR (même structure, contenu traduit)
- `image.PNG` — Image de fond hero
- Balises `hreflang` EN↔FR sur toutes les pages
- Nav FR : Accueil, Approche, Services, Équipe, Contact

## Stack
- HTML/CSS pur, pas de JS, pas de build
- Chaque page embarque son propre CSS inline (pas de fichier CSS partagé)

## Design system
- Fonts : EB Garamond (titres), Inter (body), JetBrains Mono (technique)
- Variables : `--bg` #f7f4ef, `--bg-warm` #f0ece4, `--ink` #1a1a2e, `--bordeaux` #c42838, `--bleu` #4870d0, `--gris` #484858
- Breakpoint responsive : 860px
- Patterns récurrents : datum cards (bg-warm, border-top bordeaux, hover lift), gate cards (border ink), dark blocks

## Nav & Footer
- Nav : `position: fixed; left:0; right:0;` — pleine largeur, pas de max-width
- Footer : même padding que nav (1.25rem vertical), pleine largeur
- Bottom contact : `contact@veritasquant.com or contact us` sur toutes les pages (sauf contact.html)

## Déploiement
- Repo GitHub : `youpiofficiel/veritasquant` (public)
- GitHub Pages : branche master, root
- URL : https://youpiofficiel.github.io/veritasquant/
