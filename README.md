<div align="center">

# 💗 I Love You

### A small interactive web experience made to say something simple:

> **I love you.**

<br>

<a href="https://i-love-you-mwaah-rho.vercel.app">
  <strong>💞 Open the Live Experience</strong>
</a>

<br><br>

<a href="https://github.com/Hidden-Rhythm/I-love-you">
  <img src="https://img.shields.io/badge/Source-GitHub-181717?style=for-the-badge&logo=github" alt="GitHub">
</a>
<a href="https://i-love-you-mwaah-rho.vercel.app">
  <img src="https://img.shields.io/badge/Live-Website-ff4d6d?style=for-the-badge&logo=vercel" alt="Live Website">
</a>
<a href="#">
  <img src="https://img.shields.io/badge/HTML-CSS-JS-orange?style=for-the-badge" alt="HTML CSS JavaScript">
</a>

</div>

---

## 💌 What Is This?

**I Love You** is an interactive romantic web experience built with vanilla **HTML, CSS, and JavaScript**.

Instead of putting everything on one page, the experience is split into multiple stages. Each page progresses the interaction, creating a small story that eventually leads to the final response.

It combines:

* 💗 Romantic messages
* 🎞️ Animated GIFs
* ✨ CSS animations
* 🖱️ Interactive buttons
* 📖 Multi-page storytelling
* 💞 Yes / No interaction
* 🎨 Custom visual effects
* 📱 Browser-based experience

---

## 🌹 The Experience

```text
                    ┌──────────────────┐
                    │   First Page     │
                    │   Introduction  │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │     Page 1       │
                    │  Story / Message │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │     Page 2       │
                    │  More Feelings   │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │     Page 3       │
                    │  The Question    │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │     Page 4       │
                    │   "Will You?"    │
                    └────────┬─────────┘
                             │
                    ┌────────┴────────┐
                    ▼                 ▼
              ┌───────────┐     ┌───────────┐
              │    YES    │     │     NO    │
              └─────┬─────┘     └─────┬─────┘
                    │                 │
                    ▼                 ▼
              💗 Final Flow      😭 Reactions
```

---

## ✨ Features

| Feature                 | Description                                       |
| ----------------------- | ------------------------------------------------- |
| 💗 Interactive Story    | The experience unfolds through multiple pages     |
| 🎞️ GIF Animations      | Custom GIF reactions throughout the experience    |
| 💌 Romantic Messages    | Personalized messages and interactions            |
| 🖱️ Interactive Buttons | User-driven navigation and responses              |
| ❤️ Yes / No Flow        | Interactive response sequence                     |
| 🎨 Custom CSS           | Individual styling for each stage                 |
| ✨ JavaScript Effects    | Dynamic page interactions and animations          |
| 😭 Reaction States      | Different GIFs and responses based on interaction |
| 📱 Browser Based        | Runs directly in a modern web browser             |
| 🧩 Modular Pages        | Each stage has its own HTML/CSS/JS files          |

---

## 🎞️ GIF Collection

The project includes a dedicated asset collection used for reactions and visual storytelling.

```text
Pages/Assets/
├── angry.gif
├── attitude.gif
├── bg.gif
├── depressed.gif
├── handsome.gif
├── hi.gif
├── hug.gif
├── kiss.gif
├── love.gif
├── sad.gif
├── smart.gif
├── smart1.gif
├── wall6.gif
├── window.gif
└── logo.png
```

These assets allow the interaction to change visually depending on what happens during the experience.

---

## 🧩 Project Structure

```text
I-love-you/
│
├── index.html
├── firstPage.css
├── firstPage.js
├── style.css
├── design.txt
│
├── Pages/
│   ├── Assets/
│   │   ├── angry.gif
│   │   ├── attitude.gif
│   │   ├── bg.gif
│   │   ├── depressed.gif
│   │   ├── handsome.gif
│   │   ├── hi.gif
│   │   ├── hug.gif
│   │   ├── kiss.gif
│   │   ├── love.gif
│   │   ├── sad.gif
│   │   ├── smart.gif
│   │   ├── smart1.gif
│   │   ├── wall6.gif
│   │   └── window.gif
│   │
│   ├── Page 1/
│   │   ├── secondPage.html
│   │   ├── secondPage.css
│   │   └── secondPage.js
│   │
│   ├── Page 2/
│   │   ├── thirdPage.html
│   │   ├── thirdPage.css
│   │   └── thirdPage.js
│   │
│   ├── Page 3/
│   │   └── forthPage.html
│   │
│   ├── Page 4/
│   │   ├── ask.html
│   │   ├── ask.css
│   │   └── ask.js
│   │
│   ├── Page 5/
│   │   ├── yes.html
│   │   ├── yes.css
│   │   ├── yes.js
│   │   └── yes_anime.js
│   │
│   ├── Page 6/
│   │   ├── no1.html
│   │   ├── no1.css
│   │   └── no1.js
│   │
│   ├── Page 7/
│   │   ├── no2.html
│   │   ├── no2.css
│   │   └── no2.js
│   │
│   └── Page 8/
│       ├── no3.html
│       ├── no3.css
│       └── no3.js
│
├── package.json
├── package-lock.json
└── requirements.txt
```

---

## 🎭 Interaction Paths

The project has separate paths for different responses.

### 💖 YES

The positive path leads into the dedicated **Page 5** experience:

```text
Question
   ↓
YES
   ↓
yes.html
   ↓
yes.js
   ↓
yes_anime.js
   ↓
💗 Animated Ending
```

### 😭 NO

The negative response has its own progression:

```text
NO
 ↓
Page 6
 ↓
Page 7
 ↓
Page 8
 ↓
Different reactions / messages
```

This makes the interaction feel more like a conversation rather than a simple static webpage.

---

## 🛠️ Built With

| Technology | Purpose                      |
| ---------- | ---------------------------- |
| HTML5      | Page structure               |
| CSS3       | Layout, styling & animations |
| JavaScript | Interactions & navigation    |
| GIF        | Animated reactions & visuals |
| npm        | Project/package management   |

No frontend framework is required for the core experience.

---

## 🚀 Run Locally

Clone the repository:

```bash
git clone https://github.com/Hidden-Rhythm/I-love-you.git
cd I-love-you
```

Then serve the project with any static web server.

For example:

```bash
python -m http.server 8000
```

Open:

```text
http://localhost:8000
```

> Using a local web server is recommended instead of opening the HTML files directly, especially when navigating between multiple pages and assets.

---

## 🎨 Customization

Most of the experience can be customized directly through the individual HTML, CSS and JavaScript files.

### Messages

Edit the relevant HTML files inside:

```text
Pages/Page 1/
Pages/Page 2/
Pages/Page 3/
Pages/Page 4/
Pages/Page 5/
Pages/Page 6/
Pages/Page 7/
Pages/Page 8/
```

### Styling

Each page has its own stylesheet, making it easy to customize:

* Colors
* Fonts
* Spacing
* Animations
* Backgrounds
* Buttons
* Layout

### Reactions

Replace or add GIFs inside:

```text
Pages/Assets/
```

Then reference them from the relevant HTML/CSS/JS file.

---

## 🌐 Live

### 💞 Live Website

**i-love-you-mwaah-rho.vercel.app**

The complete interactive experience is available online.

### 📦 Source Code

**Hidden-Rhythm/I-love-you**

The complete source is available in this repository.

---

## 💭 Why I Made This

Sometimes you don't need a huge application.

Sometimes you just need:

```text
a browser
+ a little code
+ some animations
+ way too many GIFs
+ one very important question

        ↓

     ❤️
```

A tiny web project can still mean a lot.

---

<div align="center">

### Made with code, chaos & a little bit of love. 💗

**Hidden_Rhythm**

</div>
