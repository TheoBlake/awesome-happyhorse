# Awesome HappyHorse-1.0 🎠

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

| [English](./README.md) | [简体中文](./README-zh.md) | [Deutsch](./README-de.md) | [Francais](./README-fr.md) | [Espanol](./README-es.md) | [日本語](./README-ja.md) |

> 面向 **HappyHorse-1.0** 的提示词、基准测试与生成案例精选。

这个仓库用于沉淀 HappyHorse-1.0 的可复现 Prompt 案例。  
当前先基于公开 Arena 信息搭建，后续会随着官方信息发布持续更新。

---

## 📖 目录

1. [目前已确认信息](#1-目前已确认信息)
2. [示例 Prompt 与本地视频](#2-示例-prompt-与本地视频)
3. [基准记录模板](#3-基准记录模板)
4. [贡献方式](#4-贡献方式)
5. [路线图](#5-路线图)
6. [免责声明](#6-免责声明)

---

## 1. 目前已确认信息

基于 Artificial Analysis 的公开帖文（2026-04-08）：

> We’ve added a new pseudonymous video model to our Text to Video and Image to Video Arenas.  
> ‘HappyHorse-1.0’ is currently landing in the #1 spot for Text and Image to Video (No Audio) and the #2 spot for Text and Image to Video (With Audio).  
> Further details coming soon.

### 已确认信号

- 在 Text/Image to Video（**无音频**）维度排名 **#1**
- 在 Text/Image to Video（**有音频**）维度排名 **#2**
- 公开示例中对比了以下模型：
  - Dreamina Seedance 2.0
  - Kling 3.0 Pro
  - grok-video-imagine
  - PixVerse V6

---

## 2. 示例 Prompt 与本地视频

### 2.1 Prompt [1/4] - 呼啦圈动作控制

**Prompt：**

```text
A hula hoop spinning on a kid's waist, gradually climbing to their chest, then dropping to knees, then ...
```

**本地视频：** [./videos/prompt-1-hula-hoop.mp4](./videos/prompt-1-hula-hoop.mp4)

**观察点：**
- 长时序动作连贯性（waist -> chest -> knees）
- 呼啦圈轨迹稳定性
- 人体与道具交互质量

### 2.2 Prompt [2/4] - 高尔夫滚边计数 + 音频

**Prompt：**

```text
A golf ball in a cup rolling around the rim three times before finally dropping in. The golfer's body language matches each rotation. Audio: Ball rattle, exhale, plop.
```

**本地视频：** [./videos/prompt-2-golf-ball.mp4](./videos/prompt-2-golf-ball.mp4)

**观察点：**
- 精确动作计数（是否严格 3 圈）
- 小物体物理表现
- 音频事件与动作时机对齐

### 2.3 Prompt [3/4] - 倒影行为 + 音频

**Prompt：**

```text
A cat staring at its own reflection in a toaster, paw tapping the chrome surface. The distorted cat reflection taps back. Audio: Paw taps, confused meow.
```

**本地视频：** [./videos/prompt-3-cat-toaster.mp4](./videos/prompt-3-cat-toaster.mp4)

**观察点：**
- 金属反射和畸变真实性
- 主体与倒影的交互时序
- 敲击声和猫叫同步性

### 2.4 Prompt [4/4] - 拉花流体细节 + 音频

**Prompt：**

```text
A barista creating latte art by pouring steamed milk into espresso. The white milk submerges beneath the brown crema initially, then breaks through the surface as the cup fills. The barista's wrist makes precise oscillating movements, creating a rosetta pattern. The milk and espresso maintain their distinct colors while interacting at the boundary. Audio: The gentle pour of liquid, the hiss of the steam wand in the background.
```

**本地视频：** [./videos/prompt-4-latte-art.mp4](./videos/prompt-4-latte-art.mp4)

**观察点：**
- 流体边界保持（milk vs crema）
- 手腕微动作精度
- 环境音氛围一致性

---

## 3. 基准记录模板

新增案例建议统一记录以下字段：

1. **模型版本**：`HappyHorse-1.0`
2. **模式**：`T2V` 或 `I2V`
3. **音频设置**：`with-audio` / `no-audio`
4. **Prompt**：原文或改写版
5. **生成参数**：时长、分辨率、seed（如可用）
6. **观察结论**：动作控制、物理合理性、风格稳定性
7. **失败案例**：计数错误、结构崩坏、音画不同步

---

## 4. 贡献方式

欢迎提交 HappyHorse-1.0 实测案例。

建议提交内容：
- Prompt 原文
- 模式与音频设置
- 生成参数（可公开部分）
- 输出文件或链接
- 简要分析（优点 + 失败点）

---

## 5. 路线图

- [ ] 在 `prompts/` 下增加分类文档
- [ ] 增加一致性/物理/音画同步打分卡
- [ ] 增加与基线模型的并排对比
- [ ] 官方文档发布后补充入口与参数说明

---

## 6. 免责声明

- 本仓库为社区整理，不代表任何官方立场。
- 当前信息仍有限，后续会根据公开信息持续更新。
