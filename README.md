# 🔎 Discovery Lense

> _“What if a magnifying glass could gently float across a map and pretend it was doing something extremely important?”_

Welcome to **Discovery Lense** — a tiny front-end visual experiment where CSS animations, masking, and an unreasonable amount of viewport units come together to create a floating magnifying glass illusion.

Yes.  
It moves.  
Yes.  
It blurs.  
Yes.  
It is aggressively specific about screen size.

---

## 🌐 Live Demo

🔗 **Deployed here:**  
[https:/link here](https://nikhil-kumawat369.github.io/Discovery-Lense-mini/)

### 🚫 Important Note Before You Click

If you are not on a 1920 × 1080 display:

Please reconsider.

It is terribly optimized for anything else.

>This is not a bug.
>This is a deliberate design decision.
>Do not ask why.

---

## 🖥️ Display Optimization (Extremely Important.)

### ⚠️ WARNING

This project is:

>Perfectly optimized only for 1920 × 1080 displays.

- Not 1366×768.
- Not 1440p.
- Not ultrawide.
- Not your tablet.
- Not your cousin’s laptop.

Only 1920 × 1080.

If you open this on any other resolution :

- The alignment may break

- The magnifying glass may wander off

- The mask might reveal chaos

- You may question everything

And before you ask:

>“Why is it optimized only for that resolution?”

Don’t.

Just don’t.

## ✨ What This Is

**Discovery Lense** is a purely front-end project that:

- 🗺️ Displays a full-screen map  
- 🌫️ Applies a blurred overlay layer  
- 🔵 Uses a circular CSS mask to reveal a sharp portion beneath  
- 🔎 Animates a magnifying glass across the screen  
- 🎞️ Synchronizes the magnifying glass and mask animation perfectly  
- 🧠 Makes you feel like you engineered something far more complex than you did  

Built entirely with:

- HTML  
- CSS  
- `backdrop-filter`  
- `mask-image`  
- Keyframe animations  
- Viewport units  
- Questionable optimism  

---

## 🎬 How It Works

There are three main layers working together:

### 1️⃣ Blurred Layer

Applies:

```css
backdrop-filter: blur(5px);
```

This creates the frosted-glass effect over the entire map.

## 2️⃣ Masking Layer

Uses:

```CSS
mask-image: url(circle.svg);
mask-position;
mask-size;
```

This layer reveals the sharp version of the map in a circular area — simulating the magnifying lens.

The animation adjusts mask-position over time to stay aligned with the magnifying glass.

## 3️⃣ Magnifying Glass Blueprint

A floating PNG that:

- Animates using transform: translate()

- Is synchronized with the mask animation

- Exists purely to look impressive

## 🛠️ Technologies Used

- HTML5

- CSS3

- CSS Animations

- CSS Masking

- backdrop-filter

- Viewport Units (a lot of them)

## 📂 Project Structure

    Discovery-Lense-mini/
    │
    ├── index.html
    ├── style.css
    └── Images/
        ├── map.png
        ├── magnifyingGlass.png
        └── circle.svg

## 🎯 Why This Exists

Because:

- CSS masks are underrated

- backdrop-filter is cool

- Animations make everything better

- Sometimes you just want to build something visually satisfying

## 🚀 Future Improvements (Maybe)

- Responsive support (big maybe)

- Mouse tracking

- Performance optimization

- Not being resolution-dependent

- Emotional growth

## 📜 License

>This project is open for learning and experimentation.
>You may modify, distribute, or expand it freely.

---

## 👤 Author

Developed by: Nikhil Kumawat
<br>
Language: HTMl | CSS
<br>
Project: DIscovery Lense

>“Adjust the lens — clarity is just a perspective away.”

---

## ⭐ Final Note

This project is a small creative front-end experiment.

It’s not meant to scale.
It’s not meant to adapt.
It’s meant to exist beautifully —

on 1920 × 1080 —

and nowhere else.

> **Don’t ask why. Some mysteries are better left at 1920 × 1080**

>⭐ If you like this project, consider giving it a star!
