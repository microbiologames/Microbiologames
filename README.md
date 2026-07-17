# 🦠 Microbiologames

Une petite collection de mini-jeux et outils arcade sur le thème de la
microbiologie, jouables directement dans le navigateur.

**▶ Jouer en ligne : https://microbiologames.github.io/Microbiologames/**
Supporter la création : https://patreon.com/Microbiologames?utm_medium=unknown&utm_source=join_link&utm_campaign=creatorshare_creator&utm_content=copyLink

---

## Les jeux

### Biofilm Simulator — Arcade Edition (V5.0)

Incarne une bactérie et bâtis un biofilm dans une canalisation industrielle :
adhère à la paroi, fais croître ta colonie, sécrète ta matrice (EPS), sporule
sous stress et survis aux cycles de nettoyage (NEP/CIP). Objectif : colmater la
canalisation à 100 % avant l'éradication de la communauté.

Points forts de cette version :

- **Communauté multi-espèces** : les bactéries exogènes capturées s'intègrent et
  se reproduisent ; la diversité rend le biofilm plus résilient et plus productif.
- **NEP variés** (alcalin, acide, oxydant, thermique), chaque espèce ayant son
  propre profil de résistance.
- **Quorum sensing** : matrice, sporulation et dispersion se débloquent au-delà
  d'un seuil de densité.
- **Sporulation induite par le stress** et **coûts en ATP dynamiques**.
- **Jouable au clavier ou au tactile**, avec écran tutoriel et **codex
  scientifique** intégré.

### Microbes Fighter — Bactérie vs Microbiologiste (V1.0)

Un jeu de combat en 2 manches gagnantes façon borne d'arcade. La **bactérie
« vicieuse »** attaque à distance et se protège ; le **microbiologiste** riposte
en appliquant les barrières de la technologie des *hurdles* (pH, aw, thermique…).
Jouable à 1 ou 2 joueurs, chaque combattant pouvant être confié au CPU pour
s'entraîner seul. Métaphore ludique de l'équilibre entre contamination et
maîtrise des procédés.

### Microbio Paint (V1.0)

Un bac à sable de **microbiologie prévisionnelle**. On « peint » des bactéries
(*Listeria monocytogenes*, *Salmonella enterica*) sur une matrice alimentaire,
on règle les champs environnementaux — température, pH, aw et traitement
thermique — puis on lance la simulation. Le modèle repose sur le concept gamma
(μ = μopt × γT × γpH × γaw) et une inactivation thermique D/z simplifiée, avec
courbe de croissance en direct, populations en log10 et diagnostic local.
Outil pédagogique — ne valide ni durée de vie, ni procédé, ni limite HACCP.
Charte graphique ADRIA.

### Échelle du monde microbien (V1.0)

Un outil pédagogique : un « vol » à travers les échelles, du virus de la grippe
(≈ 100 nm) au grain de sel (≈ 0,5 mm), en passant par *E. coli*, une conidie de
*Penicillium*, une microalgue, une levure, une cellule animale, une cellule
végétale et une paramécie — tous représentés à leur **taille relative réelle**,
avec barre d'échelle, champ de vision et **tailles issues de publications à
comité de lecture**. Charte graphique ADRIA (glaz #00A9B2, jaune #FFDD00).

---



## Structure du dépôt

```
Microbiologames/
├── index.html                    ← page d'accueil (arcade)
├── biofilm_simulator.html        ← Biofilm Simulator
├── microbes-fighter.html         ← Microbes Fighter
├── microbio-paint.html           ← Microbio Paint
└── echelle_microorganismes.html  ← Échelle du monde microbien
```

Pour ajouter un jeu : déposer son fichier `.html`, puis copier un bloc
« carte de jeu » (`<a class="game-card">`) dans `index.html` en adaptant le lien,
le titre, la version et la description.

---

## Licence

© 2026 Nicolas Nguyen Van Long — **Tous droits réservés.**

Ces jeux sont proposés gratuitement, à des fins de divertissement personnel.
La consultation du code source (inhérente à toute page web) est tolérée, mais
toute copie, modification, redistribution ou réutilisation du code, en tout ou
partie, est **interdite sans l'autorisation écrite préalable de l'auteur**.
