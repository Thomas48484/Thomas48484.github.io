---
layout: single
title: "Game 1"
permalink: /projects/agarart/

header:
  overlay_image: /assets/images/game1-header.jpg
  overlay_filter: 0.4
  caption: "Game 1 - Unity Project"
---

# Overview

This project is a short description of the game. Explain what it is, what inspired it, and what the player does.

---

## 🎥 Gameplay Video

<div class="video-container">
<iframe width="100%" height="400"
src="https://www.youtube.com/embed/VIDEO_ID"
title="Game Video"
frameborder="0"
allowfullscreen>
</iframe>
</div>

---

## 🧠 How It Works

### Core Mechanics

Explain your mechanics here:

- Movement system
- Scoring system
- AI behavior

---

## 💻 Code Breakdown

### Player Controller

```csharp
void Update()
{
    float move = Input.GetAxis("Horizontal");
    transform.Translate(Vector3.right * move * speed * Time.deltaTime);
}
