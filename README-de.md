# Awesome HappyHorse-1.0 🎠

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

| [English](./README.md) | [简体中文](./README-zh.md) | [Deutsch](./README-de.md) | [Francais](./README-fr.md) | [Espanol](./README-es.md) | [日本語](./README-ja.md) |

> Eine kuratierte Sammlung von Prompts, Benchmark-Notizen und Generierungsbeispielen fur **HappyHorse-1.0**.

Dieses Repository sammelt reproduzierbare Prompt-Falle fur HappyHorse-1.0.  
Der aktuelle Inhalt basiert auf offentlich verfugbaren Arena-Beispielen und wird weiter ausgebaut.

---

## 📖 Inhaltsverzeichnis

1. [Was bisher bekannt ist](#1-was-bisher-bekannt-ist)
2. [Beispiel-Prompts mit lokalen Videos](#2-beispiel-prompts-mit-lokalen-videos)
3. [Benchmark-Vorlage](#3-benchmark-vorlage)
4. [Mitwirken](#4-mitwirken)
5. [Roadmap](#5-roadmap)
6. [Hinweis](#6-hinweis)

---

## 1. Was bisher bekannt ist

Basierend auf dem offentlichen Beitrag von Artificial Analysis (2026-04-08):

> We’ve added a new pseudonymous video model to our Text to Video and Image to Video Arenas.  
> ‘HappyHorse-1.0’ is currently landing in the #1 spot for Text and Image to Video (No Audio) and the #2 spot for Text and Image to Video (With Audio).  
> Further details coming soon.

- **#1** bei Text/Image to Video (**ohne Audio**)
- **#2** bei Text/Image to Video (**mit Audio**)
- Offentliche Vergleiche mit: Dreamina Seedance 2.0, Kling 3.0 Pro, grok-video-imagine, PixVerse V6

---

## 2. Beispiel-Prompts mit lokalen Videos

### Prompt [1/4]
**Prompt:** `A hula hoop spinning on a kid's waist, gradually climbing to their chest, then dropping to knees, then ...`  
**Lokales Video:** [./videos/prompt-1-hula-hoop.mp4](./videos/prompt-1-hula-hoop.mp4)

### Prompt [2/4]
**Prompt:** `A golf ball in a cup rolling around the rim three times before finally dropping in. The golfer's body language matches each rotation. Audio: Ball rattle, exhale, plop.`  
**Lokales Video:** [./videos/prompt-2-golf-ball.mp4](./videos/prompt-2-golf-ball.mp4)

### Prompt [3/4]
**Prompt:** `A cat staring at its own reflection in a toaster, paw tapping the chrome surface. The distorted cat reflection taps back. Audio: Paw taps, confused meow.`  
**Lokales Video:** [./videos/prompt-3-cat-toaster.mp4](./videos/prompt-3-cat-toaster.mp4)

### Prompt [4/4]
**Prompt:** `A barista creating latte art by pouring steamed milk into espresso. The white milk submerges beneath the brown crema initially, then breaks through the surface as the cup fills. The barista's wrist makes precise oscillating movements, creating a rosetta pattern. The milk and espresso maintain their distinct colors while interacting at the boundary. Audio: The gentle pour of liquid, the hiss of the steam wand in the background.`  
**Lokales Video:** [./videos/prompt-4-latte-art.mp4](./videos/prompt-4-latte-art.mp4)

---

## 3. Benchmark-Vorlage

1. **Model/Version**: `HappyHorse-1.0`
2. **Modus**: `T2V` oder `I2V`
3. **Audio**: `with-audio` / `no-audio`
4. **Prompt**: Original oder bearbeitet
5. **Einstellungen**: Dauer, Auflosung, Seed (falls verfugbar)
6. **Beobachtungen**: Bewegung, Physik, Stabilitat
7. **Fehlerfalle**: Zahlfehler, Geometrieprobleme, Audio-Desync

---

## 4. Mitwirken

Beitrage sind willkommen. Bitte Prompt, Modus, Einstellungen, Ergebnislink und kurze Analyse angeben.

---

## 5. Roadmap

- [ ] Kategorien unter `prompts/` hinzufugen
- [ ] Scorecards fur Konsistenz/Physik/Audio-Sync
- [ ] Side-by-side Vergleiche mit Baseline-Modellen

---

## 6. Hinweis

Community-kuratiertes Repository, keine offizielle Quelle. Inhalte werden mit neuen Informationen aktualisiert.
