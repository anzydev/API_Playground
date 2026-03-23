<div align="center">
  <img src="https://media.giphy.com/media/l0ExhcMymdL6TrZ84/giphy.gif" width="100%" alt="Art Deco Header Banner" style="max-height: 200px; object-fit: cover; border: 2px solid #D4AF37;">

  <br />
  <br />

  <h1 style="color: #D4AF37; font-family:serif;">✨ PUBLIC API PLAYGROUND ✨</h1>
  <h3><i>The "Gatsby" Edition — Explore Real APIs in Luxury</i></h3>
  
  <p>
    An interactive playground to explore real public APIs — fetch random dogs, jokes, user profiles, and posts in a <b>visually stunning, highly-polished Art Deco interface</b>.
  </p>

  <p>
    <a href="#-features"><img src="https://img.shields.io/badge/Features-Gold-D4AF37?style=for-the-badge&logoColor=1A1A1A&color=D4AF37" alt="Features"></a>
    <a href="#-tech-stack"><img src="https://img.shields.io/badge/Tech_Stack-Vanilla_JS-0A0A0A?style=for-the-badge&logoColor=F2F0E4&color=0A0A0A" alt="Tech Stack"></a>
    <a href="#-apis-used"><img src="https://img.shields.io/badge/APIs-4_Available-D4AF37?style=for-the-badge&logoColor=1A1A1A&color=D4AF37" alt="APIs"></a>
  </p>
</div>

---

## 🏛️ The Design Philosophy

This project rejects the modern "soft SaaS" minimalism in favor of **maximalist restraint**. It embraces the visual language of the machine age meeting high society, combining **opulence, mathematical precision, and architectural grandeur.**

> *"Art Deco is the visual embodiment of the Roaring Twenties — an era of jazz, prosperity, and unbridled optimism."*

### 🎨 Visual Signatures
- **Obsidian & Gold Palette**: Deep `#0A0A0A` blacks paired with radiant metallic `#D4AF37` gold.
- **Sharp Geometry**: 0px border radii, stepped ziggurat corners, and rotated diamond containers.
- **Theatrical Animations**: 3D perspective tilts, sunburst radial gradients, and scroll-triggered reveals.
- **Champagne Particle System**: A custom canvas-based particle engine featuring floating gold dust that gently repels from the user's cursor.
- **Classical Typography**: High-contrast pairing of *Marcellus* (headings) and *Josefin Sans* (body text).

---

## ⚡ Features

### 1. Interactive 3D & Particle Engine 🪄
The background features a full-page **HTML5 Canvas particle system** with floating gold particles that react to your mouse movements. Hero titles and result cards feature **interactive 3D CSS tilt effects** for a tactile, "premium" feel.

### 2. Four Unique API Explorers 🔍

<details open>
<summary><b style="font-size: 1.2rem; color: #D4AF37; cursor:pointer;">🐶 Dog Finder</b></summary>
<br/>
Fetches a random image of a dog breed from the <a href="https://dog.ceo/dog-api/">Dog API</a>.
<ul>
  <li>Images presented in luxury double-border frames.</li>
  <li>Custom URL parsing to extract and format the exact breed name.</li>
  <li>Built-in "Copy URL" functionality with custom toast notifications.</li>
</ul>
</details>

<details open>
<summary><b style="font-size: 1.2rem; color: #D4AF37; cursor:pointer;">😂 Joke Generator</b></summary>
<br/>
Delivers random two-part jokes using the <a href="https://github.com/15Dkatz/official_joke_api">Official Joke API</a>.
<ul>
  <li>Highlights punchlines with a glowing cyan-gold effect.</li>
</ul>
</details>

<details open>
<summary><b style="font-size: 1.2rem; color: #D4AF37; cursor:pointer;">👤 Random User</b></summary>
<br/>
Generates fictional identities from around the world using the <a href="https://randomuser.me/">Random User Generator</a>.
<ul>
  <li>Displays high-res avatars in perfectly circular, glowing gold frames.</li>
  <li>Pulls comprehensive data including name, email, location, age, and phone number.</li>
</ul>
</details>

<details open>
<summary><b style="font-size: 1.2rem; color: #D4AF37; cursor:pointer;">📄 Post Viewer</b></summary>
<br/>
Fetches sample mock-data posts from <a href="https://jsonplaceholder.typicode.com/">JSONPlaceholder</a>.
<ul>
  <li>Cycles sequentially through a catalog of 100 mock posts.</li>
  <li>Displays elegant typography for title and body formatting.</li>
</ul>
</details>

---

## 🛠️ Tech Stack

This project was built deliberately with **Zero Frameworks**. It relies purely on the foundational web triad to maximize performance and demonstrate core engineering fundamentals:

| Core Technology | Usage Overview |
| :--- | :--- |
| **HTML5** | Semantic structure, accessibility features (`aria-hidden`), `<canvas>` element for the particle engine. |
| **CSS3** | Extensive use of custom properties (variables), `clip-path` geometry, 3D `perspective` math, overlapping pseudo-elements, complex keyframe animations. |
| **Vanilla JS** | Modern `async/await` fetch logic, `IntersectionObserver` for scroll reveals, `requestAnimationFrame` for the 60FPS particle loop, and 3D pointer geometry calculations. |

---

## 🚀 Getting Started

To run this beautifully crafted playground locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/anzydev/fetcher.git
   cd fetcher
   ```
2. **Serve the files locally:**
   You can use any local web server. For instance, with Python:
   ```bash
   python3 -m http.server 8080
   ```
3. **Open the application:**
   Navigate your browser to `http://localhost:8080` (or whichever port your server is using).

---

<p align="center">
  <br/>
  ◆ ◆ ◆
  <br/>
  <i>Crafted with precision & public APIs.</i>
</p>
