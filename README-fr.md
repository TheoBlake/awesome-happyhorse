# Awesome HappyHorse-1.0 🎠

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

| [English](./README.md) | [简体中文](./README-zh.md) | [Deutsch](./README-de.md) | [Francais](./README-fr.md) | [Espanol](./README-es.md) | [日本語](./README-ja.md) |

> Une collection de prompts, notes de benchmark et exemples de generation pour **HappyHorse-1.0**.

Ce depot rassemble des cas reproductibles pour HappyHorse-1.0.  
Le contenu initial est base sur des exemples publics de l'Arena.

---

## 📖 Sommaire

1. [Ce que nous savons](#1-ce-que-nous-savons)
2. [Prompts d'exemple avec videos locales](#2-prompts-dexemple-avec-videos-locales)
3. [Modele de benchmark](#3-modele-de-benchmark)
4. [Contribution](#4-contribution)
5. [Roadmap](#5-roadmap)
6. [Avertissement](#6-avertissement)

---

## 1. Ce que nous savons

Selon le post public d'Artificial Analysis (2026-04-08):

> We’ve added a new pseudonymous video model to our Text to Video and Image to Video Arenas.  
> ‘HappyHorse-1.0’ is currently landing in the #1 spot for Text and Image to Video (No Audio) and the #2 spot for Text and Image to Video (With Audio).  
> Further details coming soon.

- **#1** en Text/Image to Video (**sans audio**)
- **#2** en Text/Image to Video (**avec audio**)
- Comparaisons publiques avec: Dreamina Seedance 2.0, Kling 3.0 Pro, grok-video-imagine, PixVerse V6

---

## 2. Prompts d'exemple avec videos locales

### Prompt [1/4]
**Prompt:** `A hula hoop spinning on a kid's waist, gradually climbing to their chest, then dropping to knees, then ...`  
**Video locale:** [./videos/prompt-1-hula-hoop.mp4](./videos/prompt-1-hula-hoop.mp4)

### Prompt [2/4]
**Prompt:** `A golf ball in a cup rolling around the rim three times before finally dropping in. The golfer's body language matches each rotation. Audio: Ball rattle, exhale, plop.`  
**Video locale:** [./videos/prompt-2-golf-ball.mp4](./videos/prompt-2-golf-ball.mp4)

### Prompt [3/4]
**Prompt:** `A cat staring at its own reflection in a toaster, paw tapping the chrome surface. The distorted cat reflection taps back. Audio: Paw taps, confused meow.`  
**Video locale:** [./videos/prompt-3-cat-toaster.mp4](./videos/prompt-3-cat-toaster.mp4)

### Prompt [4/4]
**Prompt:** `A barista creating latte art by pouring steamed milk into espresso. The white milk submerges beneath the brown crema initially, then breaks through the surface as the cup fills. The barista's wrist makes precise oscillating movements, creating a rosetta pattern. The milk and espresso maintain their distinct colors while interacting at the boundary. Audio: The gentle pour of liquid, the hiss of the steam wand in the background.`  
**Video locale:** [./videos/prompt-4-latte-art.mp4](./videos/prompt-4-latte-art.mp4)

---

## 3. Modele de benchmark

1. **Modele/Version**: `HappyHorse-1.0`
2. **Mode**: `T2V` ou `I2V`
3. **Audio**: `with-audio` / `no-audio`
4. **Prompt**: original ou modifie
5. **Parametres**: duree, resolution, seed (si disponible)
6. **Observations**: mouvement, physique, stabilite
7. **Echecs**: erreurs de comptage, ruptures geometriques, desynchronisation audio

---

## 4. Contribution

Contributions bienvenues. Merci d'inclure prompt, mode, parametres, resultat et analyse courte.

---

## 5. Roadmap

- [ ] Ajouter des categories dans `prompts/`
- [ ] Ajouter des scorecards (coherence/physique/audio)
- [ ] Ajouter des comparaisons cote a cote

---

## 6. Avertissement

Depot communautaire, non officiel. Le contenu sera mis a jour avec les nouvelles informations publiques.
