# Awesome HappyHorse-1.0 🎠

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

| [English](./README.md) | [简体中文](./README-zh.md) | [Deutsch](./README-de.md) | [Francais](./README-fr.md) | [Espanol](./README-es.md) | [日本語](./README-ja.md) |

> **HappyHorse-1.0** 向けのプロンプト、ベンチマークノート、生成例をまとめたキュレーションです。

このリポジトリは HappyHorse-1.0 の再現可能なプロンプト事例を蓄積します。  
初期内容は公開された Arena 事例に基づいています。

---

## 📖 目次

1. [現時点で分かっていること](#1-現時点で分かっていること)
2. [ローカル動画付きサンプルプロンプト](#2-ローカル動画付きサンプルプロンプト)
3. [ベンチマーク記録テンプレート](#3-ベンチマーク記録テンプレート)
4. [コントリビュート](#4-コントリビュート)
5. [ロードマップ](#5-ロードマップ)
6. [免責事項](#6-免責事項)

---

## 1. 現時点で分かっていること

Artificial Analysis の公開投稿（2026-04-08）より:

> We’ve added a new pseudonymous video model to our Text to Video and Image to Video Arenas.  
> ‘HappyHorse-1.0’ is currently landing in the #1 spot for Text and Image to Video (No Audio) and the #2 spot for Text and Image to Video (With Audio).  
> Further details coming soon.

- Text/Image to Video（**音声なし**）で **#1**
- Text/Image to Video（**音声あり**）で **#2**
- 公開比較対象: Dreamina Seedance 2.0, Kling 3.0 Pro, grok-video-imagine, PixVerse V6

---

## 2. ローカル動画付きサンプルプロンプト

### Prompt [1/4]
**Prompt:** `A hula hoop spinning on a kid's waist, gradually climbing to their chest, then dropping to knees, then ...`  
**ローカル動画:** [./videos/prompt-1-hula-hoop.mp4](./videos/prompt-1-hula-hoop.mp4)

### Prompt [2/4]
**Prompt:** `A golf ball in a cup rolling around the rim three times before finally dropping in. The golfer's body language matches each rotation. Audio: Ball rattle, exhale, plop.`  
**ローカル動画:** [./videos/prompt-2-golf-ball.mp4](./videos/prompt-2-golf-ball.mp4)

### Prompt [3/4]
**Prompt:** `A cat staring at its own reflection in a toaster, paw tapping the chrome surface. The distorted cat reflection taps back. Audio: Paw taps, confused meow.`  
**ローカル動画:** [./videos/prompt-3-cat-toaster.mp4](./videos/prompt-3-cat-toaster.mp4)

### Prompt [4/4]
**Prompt:** `A barista creating latte art by pouring steamed milk into espresso. The white milk submerges beneath the brown crema initially, then breaks through the surface as the cup fills. The barista's wrist makes precise oscillating movements, creating a rosetta pattern. The milk and espresso maintain their distinct colors while interacting at the boundary. Audio: The gentle pour of liquid, the hiss of the steam wand in the background.`  
**ローカル動画:** [./videos/prompt-4-latte-art.mp4](./videos/prompt-4-latte-art.mp4)

---

## 3. ベンチマーク記録テンプレート

1. **Model/Version**: `HappyHorse-1.0`
2. **Mode**: `T2V` または `I2V`
3. **Audio**: `with-audio` / `no-audio`
4. **Prompt**: 原文または編集版
5. **設定**: 長さ、解像度、seed（利用可能なら）
6. **観察**: 動き、物理、安定性
7. **失敗例**: カウントミス、形状崩れ、音ズレ

---

## 4. コントリビュート

貢献歓迎です。Prompt、モード、設定、結果、短い分析を添えてください。

---

## 5. ロードマップ

- [ ] `prompts/` にカテゴリを追加
- [ ] 一貫性/物理/音同期のスコアカード追加
- [ ] ベースラインモデルとの比較追加

---

## 6. 免責事項

このリポジトリはコミュニティ整理であり、公式情報ではありません。公開情報に合わせて更新します。
