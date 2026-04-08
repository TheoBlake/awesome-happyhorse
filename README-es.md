# Awesome HappyHorse-1.0 🎠

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

| [English](./README.md) | [简体中文](./README-zh.md) | [Deutsch](./README-de.md) | [Francais](./README-fr.md) | [Espanol](./README-es.md) | [日本語](./README-ja.md) |

> Una coleccion curada de prompts, notas de benchmark y ejemplos de generacion para **HappyHorse-1.0**.

Este repositorio reune casos reproducibles para HappyHorse-1.0.  
El contenido inicial se basa en ejemplos publicos del Arena.

---

## 📖 Tabla de contenidos

1. [Lo que sabemos hasta ahora](#1-lo-que-sabemos-hasta-ahora)
2. [Prompts de ejemplo con videos locales](#2-prompts-de-ejemplo-con-videos-locales)
3. [Plantilla de benchmark](#3-plantilla-de-benchmark)
4. [Contribuir](#4-contribuir)
5. [Roadmap](#5-roadmap)
6. [Aviso](#6-aviso)

---

## 1. Lo que sabemos hasta ahora

Segun la publicacion de Artificial Analysis (2026-04-08):

> We’ve added a new pseudonymous video model to our Text to Video and Image to Video Arenas.  
> ‘HappyHorse-1.0’ is currently landing in the #1 spot for Text and Image to Video (No Audio) and the #2 spot for Text and Image to Video (With Audio).  
> Further details coming soon.

- **#1** en Text/Image to Video (**sin audio**)
- **#2** en Text/Image to Video (**con audio**)
- Comparado publicamente con: Dreamina Seedance 2.0, Kling 3.0 Pro, grok-video-imagine, PixVerse V6

---

## 2. Prompts de ejemplo con videos locales

### Prompt [1/4]
**Prompt:** `A hula hoop spinning on a kid's waist, gradually climbing to their chest, then dropping to knees, then ...`  
**Video local:** [./videos/prompt-1-hula-hoop.mp4](./videos/prompt-1-hula-hoop.mp4)

### Prompt [2/4]
**Prompt:** `A golf ball in a cup rolling around the rim three times before finally dropping in. The golfer's body language matches each rotation. Audio: Ball rattle, exhale, plop.`  
**Video local:** [./videos/prompt-2-golf-ball.mp4](./videos/prompt-2-golf-ball.mp4)

### Prompt [3/4]
**Prompt:** `A cat staring at its own reflection in a toaster, paw tapping the chrome surface. The distorted cat reflection taps back. Audio: Paw taps, confused meow.`  
**Video local:** [./videos/prompt-3-cat-toaster.mp4](./videos/prompt-3-cat-toaster.mp4)

### Prompt [4/4]
**Prompt:** `A barista creating latte art by pouring steamed milk into espresso. The white milk submerges beneath the brown crema initially, then breaks through the surface as the cup fills. The barista's wrist makes precise oscillating movements, creating a rosetta pattern. The milk and espresso maintain their distinct colors while interacting at the boundary. Audio: The gentle pour of liquid, the hiss of the steam wand in the background.`  
**Video local:** [./videos/prompt-4-latte-art.mp4](./videos/prompt-4-latte-art.mp4)

---

## 3. Plantilla de benchmark

1. **Modelo/Version**: `HappyHorse-1.0`
2. **Modo**: `T2V` o `I2V`
3. **Audio**: `with-audio` / `no-audio`
4. **Prompt**: original o editado
5. **Parametros**: duracion, resolucion, seed (si aplica)
6. **Observaciones**: movimiento, fisica, estabilidad
7. **Fallos**: errores de conteo, roturas geometricas, desincronizacion

---

## 4. Contribuir

Contribuciones bienvenidas. Incluye prompt, modo, parametros, resultado y un analisis breve.

---

## 5. Roadmap

- [ ] Agregar categorias en `prompts/`
- [ ] Agregar scorecards de consistencia/fisica/audio
- [ ] Agregar comparaciones lado a lado

---

## 6. Aviso

Repositorio curado por la comunidad, no oficial. Se actualizara conforme aparezca mas informacion publica.
