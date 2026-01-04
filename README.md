[image_0]: https://pfst.cf2.poecdn.net/base/image/6a3afb11804680d2c7dfb2818d1134c6596931729b63940ddb49a82126c9ed27?pmaid=545151399
[image_1]: https://pfst.cf2.poecdn.net/base/image/a86cfcea8bf2d1096a0f9c33b4f8de825f358402f4b752ecc72a5e52c8bf45f5?pmaid=545151400
[image_2]: https://pfst.cf2.poecdn.net/base/image/96a21316d5835eefe7cac043d0d8ce917d60dbccf65540a8ddd77ec236ad711e?pmaid=545151401
[image_3]: https://pfst.cf2.poecdn.net/base/image/a94d2b9b05f68912d977a35eb23306504e4b12eff285d4c011a1d51ebeeba7a3?pmaid=545151403

# Visit a Friend

A dark, minimalist promotional website for **Visit a Friend** — a handcrafted adventure RPG built entirely on Scratch. This site showcases the game with striking visuals, smooth animations, and an immersive user experience.

![Built on Scratch][image_0]
![HTML5][image_1]
![CSS3][image_2]
![JavaScript][image_3]

---

## ✨ Features

### Visual Design
- **Dark void aesthetic** — Pure black background with white accents
- **Custom cursor** — Minimalist circle cursor with hover effects
- **Responsive layout** — Fully optimized for desktop and mobile devices

### Animations
- **Glitch text effect** — "VISIT A FRIEND" title scrambles on page load
- **Wave animation** — "The Narrative" header letters flip in sequentially
- **Split reveal** — "Game Features" letters slide up dramatically
- **Shimmer sweep** — "Behind The Magic" has an orange gradient sweep effect
- **Scroll-triggered reveals** — Sections fade in as you scroll
- **Counter animation** — Stats count up when entering viewport

### Interactive Elements
- **3D rotating carousel** — Gallery of game screenshots with tilt effect
- **Scroll-driven animation** — Carousel rotates as you scroll (~2.5 rotations)
- **Floating navigation dock** — Fixed bottom nav with smooth hover states
- **Hover effects** — Cards lift, images colorize, buttons transform

### Game Showcase
- **4,000+ hand-drawn sprites**
- **30,000+ Scratch blocks**
- **Multiple endings** based on player choices
- **Time-based mechanics** and survival elements
- **Epic boss battles**

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic structure |
| **CSS3** | Styling, animations, 3D transforms |
| **JavaScript** | Interactivity & scroll effects |
| **GSAP** | Advanced animations & ScrollTrigger |
| **Google Fonts** | Space Grotesk & Inter typography |
| **Boxicons** | Icon library |

---

## 📁 Project Structure

```
visit-a-friend/
├── index.html      # Main (and only) HTML file with embedded CSS/JS
└── README.md       # This file
```

This is a single-file application — all CSS and JavaScript are embedded within `index.html` for easy deployment and portability.

---

## 🚀 Getting Started

### Option 1: Direct Browser
Simply open `index.html` in any modern web browser.

### Option 2: Local Server
For the best experience (especially for scroll animations):

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

### Option 3: Deploy
This site can be deployed to any static hosting service:
- **GitHub Pages**
- **Netlify**
- **Vercel**
- **Cloudflare Pages**

---

## 🎮 Play the Game

The website links directly to the game on TurboWarp:

**[Play Visit a Friend](https://turbowarp.org/975276757/fullscreen)**

---

## 📱 Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Edge | ✅ Full |
| Mobile browsers | ✅ Responsive |

> **Note:** The 3D carousel uses CSS `animation-timeline: scroll()` which has limited browser support. In unsupported browsers, the carousel will display statically.

---

## 🎨 Customization

### Colors
Edit the CSS custom properties in `:root`:

```css
:root {
    --bg-color: #000000;
    --text-color: #e0e0e0;
    --accent-color: #ffffff;
    --scratch-orange: #ff9800;
    --border-color: rgba(255, 255, 255, 0.15);
}
```

### Content
- Update game images in the gallery section
- Modify stats numbers via `data-target` attributes
- Edit text content directly in HTML

### Animations
- Adjust timing in GSAP configurations
- Modify CSS keyframes for different effects
- Change scroll trigger points in JavaScript

---

## 📊 Stats Displayed

| Metric | Value |
|--------|-------|
| Community Views | 600+ |
| Hours Spent | 600+ |
| Scratch Blocks | 30,000+ |
| Hand-Drawn Sprites | 4,000+ |

---

## 👤 Credits

**Game Developer:** [Cyscination](mailto:cyscination@gmail.com)

**Website Technologies:**
- [GSAP](https://greensock.com/gsap/) — Animation library
- [Boxicons](https://boxicons.com/) — Icon library
- [Google Fonts](https://fonts.google.com/) — Typography
- [TurboWarp](https://turbowarp.org/) — Scratch mod for playing the game

---

## 📄 License

This project is for promotional purposes for the "Visit a Friend" Scratch game.

© 2026 Visit a Friend. All rights reserved.

---

## 🔗 Links

- **Play the Game:** [TurboWarp](https://turbowarp.org/975276757/fullscreen)
- **Scratch Profile:** [Cyscination](https://scratch.mit.edu/)
- **Contact:** cyscination@gmail.com

---

<p align="center">
  <strong>Built with ❤️ on Scratch</strong>
</p>
