# 🎬 Silent Walk — AI-Powered Ambient Video Project

> *A complete 4K ambient video created entirely using AI tools and LLM-guided workflow*

[![YouTube](https://img.shields.io/badge/Watch%20on-YouTube-red?style=for-the-badge&logo=youtube)](https://youtu.be/_ZPwCbXq0CI)
[![Midjourney](https://img.shields.io/badge/Image-Midjourney-blue?style=for-the-badge)](https://midjourney.com)
[![Suno](https://img.shields.io/badge/Music-Suno%20AI-green?style=for-the-badge)](https://suno.com)
[![DaVinci](https://img.shields.io/badge/Video-DaVinci%20Resolve%2020-orange?style=for-the-badge)](https://www.blackmagicdesign.com)
[![Claude](https://img.shields.io/badge/LLM-Claude%20AI-purple?style=for-the-badge)](https://claude.ai)

---

## 📺 Watch the Video

**Silent Walk / Bladerunner Ambient 4K / For Sleep, Study & Relaxation / 3 Hours**

🎬 [Click here to watch on YouTube](https://youtu.be/_ZPwCbXq0CI)

> *Unlisted — available via link*

---

## 🧠 Project Overview

This project demonstrates an **end-to-end AI-powered creative workflow** — from initial concept to a published 4K YouTube video — using AI image generation, AI music composition, professional video editing, and an LLM as a workflow guide throughout the entire process.

The vision: a **Blade Runner 2049-inspired ambient video** featuring a lone silhouette figure walking through a dystopian nighttime snowscape between towering alien structures, with atmospheric neon lighting and falling snow.

**Channel:** [Sound Realm Studio](https://youtube.com/@SoundRealmStudio) — *Navigate Your Imagination*

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Claude AI (LLM)** | Workflow guide, prompt engineering, troubleshooting |
| **Midjourney** | AI image generation and 4K upscaling |
| **Suno AI** | AI music composition |
| **DaVinci Resolve 20** | Color grading, particle effects, video editing, export |

---

## 🔄 Workflow

### Step 1 — Concept & Prompt Engineering
Used **Claude AI** to engineer a detailed cinematic Midjourney prompt describing the exact scene, mood, lighting, and photographic settings.

**Midjourney Prompt:**
```
A lone silhouette figure walking away in the far distance along a wet snow-melted 
sidewalk between two colossal brutalist monolithic structures at night, dystopian 
atmosphere, real life photography, the massive buildings rise out of frame with smooth 
featureless concrete-like alien surfaces, no signage or markings, sparse narrow windows 
emitting a faint amber warm glow from within, dim neon accent lights embedded along the 
building edges casting muted teal and deep orange hues, a row of low 3-foot glowing blue 
pole lights lines the sidewalk casting cold blue reflections on the wet pavement below, 
light snow dusting on the ground with the path cleared and reflective, figure is small 
and distant emphasizing isolation and scale, silent lonely mood, cold foggy air with 
volumetric light haze, extraterrestrial architectural design, ultra cinematic composition, 
deep shadows, muted color palette with blue and amber contrast, shot on Canon R5, f/2.8, 
ISO 3200, long exposure, photographic, Roger Deakins lighting 
--ar 21:9 --style raw --v 6 --q 2 --no text, signs, logos, people in foreground
```

---

### Step 2 — Image Generation & Upscaling
- Generated image in **Midjourney v6**
- Selected best result from generated variations
- Applied **Subtle 4K Upscale** to achieve maximum resolution
- Final image resolution: **3840x2160 (4K)**

---

### Step 3 — AI Music Composition
Composed two complementary ambient tracks using **Suno AI** with detailed prompts.

**Track 1 — Silent Walk**
```
[ambient] [dark-ambient] [piano] [drone] [minimal] [atmospheric] [slow-evolving] 
[instrumental] [bpm-60]

Two-layer ambient composition. Background: deep, warm synth pad playing a slow cycle 
of 3-4 low notes, repetitive and hypnotic, like a distant machine breathing. 
Foreground: simple piano, just a few notes repeating with space between them, 
melancholic and eerie, like a lone figure watching from afar. Cold atmosphere, 
mysterious, emotionally distant. For sleeping and studying.
```

**Track 2 — Silent Walk 2**
```
[ambient] [dark-ambient] [piano] [minimal] [atmospheric] [slow] [instrumental] [bpm-60]

Piano playing solo. Playing few notes.
```

---

### Step 4 — Color Grading in DaVinci Resolve 20
Used **Claude AI** to guide a manual Blade Runner-inspired teal and orange color grade:

- **Lift** wheel — pushed shadows toward cyan/teal
- **Gain** wheel — pushed highlights toward amber/orange
- **Contrast** — increased to 1.10 for cinematic depth
- **Temperature** — cooled slightly for cold winter night atmosphere
- Blacks crushed for moody shadow depth

---

### Step 5 — Particle Snow Effects in DaVinci Fusion
Built dual particle snow systems for depth layering:

- **pEmitter 1** — primary snow layer
- **pEmitter 2** — secondary depth layer
- Connected via **pRender** and **pMerge**
- Merged over image using **Screen blend mode** for clean composite

**Node Structure:**
```
pEmitter1 ──┐
             ├── pRender1 ──┐
pEmitter1_1 ─── pMerge1 ───┤
                             ▼
MediaIn1 ──────────────── Merge1 ──── MediaOut1
```

---

### Step 6 — Audio Editing & 3-Hour Loop
- Imported both Suno tracks into **DaVinci Resolve Fairlight** page
- Applied **48-frame crossfades** between tracks for seamless transitions
- Used **doubling copy-paste method** to extend to 3 hours:
  - 3 clips (~9 min) → double → double → double → double → double → 3+ hours
- Added fade in at start and fade out at end

---

### Step 7 — Export & Upload
- **Format:** MP4
- **Codec:** H.265 (Main 10)
- **Resolution:** 3840x2160 (4K Ultra HD)
- **Frame Rate:** 24fps
- **Preset:** YouTube 2160p
- Uploaded to **Sound Realm Studio** YouTube channel

---

## 🤖 LLM-Guided Workflow

A key aspect of this project was using **Claude AI** not just for prompt engineering, but as an **interactive workflow guide** throughout the entire production process:

- Engineered the Midjourney image prompt
- Guided DaVinci Resolve setup and troubleshooting
- Advised on color grading technique
- Explained Fusion particle system setup
- Assisted with audio loop strategy
- Guided YouTube channel setup and SEO optimization
- Generated LinkedIn carousel for project documentation

This demonstrates practical **LLM prompting skills** applied to a real-world creative production workflow.

---

## 📁 Repository Contents

```
├── README.md                          # This file
├── prompts/
│   ├── midjourney_prompt.txt          # Full Midjourney image prompt
│   └── suno_prompts.txt               # Suno music prompts
└── linkedin/
    └── SoundRealmStudio_Carousel.pdf  # LinkedIn project carousel
```

---

## 🎯 Skills Demonstrated

- **AI Prompt Engineering** — Midjourney, Suno, Claude
- **LLM Workflow Integration** — Using Claude as an end-to-end project guide
- **Video Production** — DaVinci Resolve 20
- **Color Grading** — Cinematic teal/orange grade
- **Visual Effects** — Particle systems in DaVinci Fusion
- **Audio Production** — Ambient music composition and loop editing
- **Content Strategy** — YouTube SEO, channel branding
- **Personal Branding** — Sound Realm Studio brand creation

---

## 📬 Connect

- **YouTube:** [Sound Realm Studio](https://youtube.com/@SoundRealmStudio) *(launching soon)*
- **LinkedIn:** Daniel | AI Content Creator / Prompt Engineer / Midjourney / Suno / DaVinci Resolve

---

*Built with AI. Guided by curiosity.*
