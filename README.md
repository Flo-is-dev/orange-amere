# Pulpe Orange

> Un design system agrumes et une landing page pour **L'Orange Amère®**,
> un produit qui n'existe pas — et c'est sans doute mieux comme ça.

![statut](https://img.shields.io/badge/statut-aigre-orange) ![humeur](https://img.shields.io/badge/humeur-mauvaise-red) ![concentré](https://img.shields.io/badge/concentr%C3%A9-0%25-yellow)

---

## C'est qui qui a écrit ça ?

> ⚠ **Avertissement honnête** ⚠

Ce code a été écrit à 99,7% par une **intelligence artificielle**
(Claude, en l'occurrence). Le 0,3% restant ce sont les fautes
d'orthographe, qui elles sont 100% humaines.

Voici, pour la postérité, la liste exhaustive de mes contributions
en tant qu'humain :

- [x] J'ai dit "fais une landing page sur l'orange amère"
- [x] J'ai dit "plus à gauche"
- [x] J'ai dit "le warning est mal centré"
- [x] J'ai dit "non non, encore plus à gauche"
- [x] J'ai cliqué sur le bouton "Approuver" environ 47 fois
- [x] J'ai dit "ralentis la vidéo"
- [x] J'ai dit "non, ralentis-la moins"
- [x] J'ai poussé sur GitHub, ça c'est moi

Et voilà, c'est tout. Le reste — la palette, les zigzags, le copywriting
ronchon, les bulles de BD, le verre SVG qui se remplit, le ré-encodage
ffmpeg de la vidéo, les commentaires en français dans le code,
le présent README — c'est l'IA.

Si quelqu'un mérite d'être remercié dans une cérémonie quelconque,
c'est elle. Personnellement, je revendique uniquement le droit moral
sur les fautes de frappe, lesquelles sont signées et notariées.

---

## Pourquoi ?

Excellente question. Honnêtement, on ne sait pas vraiment.

Au départ on voulait un design system. Puis on s'est dit qu'il fallait
une démo. Puis qu'il fallait une vraie page produit. Puis que ce serait
plus drôle si le produit était insupportable. Puis qu'un verre de jus
SVG qui se remplit au scroll, ce serait un détail mignon.

À aucun moment on ne s'est arrêté pour se demander si c'était utile.
C'est sans doute mieux comme ça.

---

## Ce qu'il y a dedans

```
pulpe-orange/
├── index.html              ← Vitrine du design system + site demo
├── orange-amere.html       ← La landing produit, avec scroll-scrub vidéo
├── pulpe-orange.css        ← Tout le design system (~1200 lignes, 17 sections)
├── favicon.svg             ← Une orange, parce qu'il fallait bien
├── orange-scroll.mp4       ← Vidéo ré-encodée (toutes les frames en keyframe)
├── orange-dance-dance-revolution.mp4  ← L'originale, gardée par sentimentalisme
└── README.md               ← Vous y êtes. Bravo.
```

---

## Ce que fait le design system

| Section              | C'est-à-dire                                                                                    |
| -------------------- | ----------------------------------------------------------------------------------------------- |
| 01 — Couleurs        | 12 tokens agrumes (orange, jaune, leaf, pulpe, zest, juice…)                                    |
| 02 — Typo            | Archivo Black, Bebas Neue, Fraunces Italic, Caveat, DM Sans, JetBrains Mono, Lilita One, Sigmar |
| 03 — Zigzag          | La bordure dentelée signature (3 variantes)                                                     |
| 04 — Boutons         | 6 variantes × 3 tailles, avec hard shadow                                                       |
| 05 — Stickers        | Étoiles bursts en clip-path                                                                     |
| 06 — Marquees        | Bandes défilantes (jaune, orange, leaf, ink)                                                    |
| 07 — Cartes          | Avec tilt et shadow offset                                                                      |
| 08 — Badges & checks | Listes à puces orange-coche                                                                     |
| 09 — Icônes          | Slice, leaf, drop, star, heart, spark, arrow (SVG masks)                                        |
| 10 — Illustrations   | Orange entière + demi-orange en CSS pur                                                         |
| 11 — Navigation      | Sticky avec brand mark                                                                          |
| 12 — Stats           | Grille de chiffres                                                                              |
| 17 — Cartoon USA     | POW! bursts, halftone, speech bubbles, warning stripes                                          |

(Les sections 13-16 ont préféré rester anonymes.)

---

## Tech stack

- HTML
- CSS
- JavaScript (vanilla, le bon vieux)
- `ffmpeg` pour le ré-encodage vidéo (`-g 1` pour scrub fluide)
- Une IA, beaucoup de patience
- Un humain, peu de patience

**Pas dans la stack** : React, Vue, Svelte, Tailwind, Webpack, Vite,
TypeScript, Storybook, ESLint, Prettier, Figma, Notion, Slack, Jira,
ou tout autre outil dont vous croyez qu'il est indispensable. Spoiler :
il ne l'est pas.

---

## Crédits

- **Inspiration visuelle** : un certain chipsier breton, qu'on
  remercie pour les idées et qu'on ne nommera pas pour des raisons légales.
- **Design system, code, copywriting, README** : Anthropic Claude
  (qui n'a jamais goûté de jus d'orange, ni de chips, mais qui se débrouille)
- **Direction artistique** : "fais ce que tu veux, mais en orange"
- **Bonne humeur** : non incluse, conformément à la marque

---

## Avertissement légal (faux)

L'Orange Amère® est un produit fictif. Aucune orange n'a été pressée,
embouteillée, ou maltraitée pendant la réalisation de ce projet.
Toute ressemblance avec un jus existant serait fortuite et probablement
décevante.

Pour votre santé, **pratiquez la patience**. Et l'humour.
Et le scroll. Beaucoup de scroll.

---

## Licence

Faites-en ce que vous voulez. On ne le saura pas. On ne veut pas le savoir.

```
SPDX-License-Identifier: MIT
```

---

<sub>_Ce README a été généré par une IA, qui assure qu'elle n'a aucune
opinion sur le sujet. Elle ment._</sub>
