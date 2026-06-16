---
layout: splash
title: "Agar.Art"
permalink: /projects/agarart/

header:
  overlay_image: /assets/images/game1.png
  overlay_filter: 0.4
  caption: "Agar.Art - Unity Project"
---

# Overview

This project is a short description of the game. Explain what it is, what inspired it, and what the player does.

---

## 🎥 Gameplay Video

<div class="video-container">
<iframe width="100%" height="800"
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
```
