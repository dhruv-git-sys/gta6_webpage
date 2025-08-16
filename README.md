# Grand Theft Auto VI Landing Page

A visually rich, animated landing page for Grand Theft Auto VI, built with React, GSAP, and Tailwind CSS. This project showcases advanced scroll-based animations, immersive video backgrounds, and responsive design, inspired by modern game marketing websites.

---

## 🚀 Features

- **Animated Hero Section:** Masked logo reveal, smooth transitions, and scroll-triggered effects.
- **Scroll-based Video Playback:** Videos play and scrub in sync with scroll using GSAP timelines.
- **Character Sections:** Highlighted sections for main characters (Jason & Lucia) with animated images and backgrounds.
- **Responsive Design:** Fully responsive layout using Tailwind CSS and custom breakpoints.
- **Custom Fonts:** GTA-inspired typography with local font assets.
- **Interactive Postcard:** Animated gradient backgrounds and video overlays.
- **Final Reveal:** Cinematic outro with logo and release date.
- **Performance Optimized:** Uses `preload`, `muted`, and `playsInline` for smooth video playback.

---

## 🛠️ Tech Stack

- **React 19**
- **GSAP** (GreenSock Animation Platform) with ScrollTrigger and React integration
- **Tailwind CSS 4**
- **Vite** for fast development and builds
- **react-responsive** for adaptive UI
- **Custom local fonts and assets**

---

## 📁 Project Structure

```
.
├── constants/              # Responsive mask settings
├── public/
│   ├── fonts/              # Custom font files
│   ├── images/             # All image assets (logos, backgrounds, etc.)
│   └── videos/             # Video backgrounds and animations
├── src/
│   ├── sections/           # All main page sections as React components
│   ├── App.jsx             # Main app layout
│   ├── main.jsx            # Entry point
│   └── index.css           # Tailwind and custom styles
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

---

## 🖥️ Local Development

### 1. **Install Dependencies**

```sh
npm install
```

### 2. **Start the Development Server**

```sh
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) to view the site.

### 3. **Build for Production**

```sh
npm run build
```

### 4. **Preview Production Build**

```sh
npm run preview
```

---

## ✨ Customization

- **Assets:** Replace images and videos in `public/images/` and `public/videos/` for your own branding.
- **Fonts:** Add or change fonts in `public/fonts/` and update `src/index.css`.
- **Animations:** Tweak GSAP timelines in each section component under `src/sections/`.

---

## 📦 Dependencies

- [`react`](https://react.dev/)
- [`gsap`](https://greensock.com/gsap/)
- [`@gsap/react`](https://www.npmjs.com/package/@gsap/react)
- [`tailwindcss`](https://tailwindcss.com/)
- [`@tailwindcss/vite`](https://www.npmjs.com/package/@tailwindcss/vite)
- [`react-responsive`](https://www.npmjs.com/package/react-responsive)
- [`vite`](https://vitejs.dev/)

---

## 📝 License

This project is for educational and demonstration purposes only. All GTA 6 assets and trademarks belong to their respective owners.

---

## 🙏 Credits

- Rockstar Games for inspiration and original GTA 6 assets.
- [GSAP](https://greensock.com/gsap/) for animation tooling.
- [Tailwind CSS](https://tailwindcss.com/) for utility-first styling.

---

## 📣 Contact

For questions or feedback, open an issue or reach out via