# SpotQ — Premium Restaurant Queue Management

> Skip the Wait. Enjoy the Experience.

SpotQ is a smart restaurant queue management platform that allows customers to join restaurant queues remotely, track their live position, receive AI-predicted waiting times, and arrive exactly when their table is ready.

---

## 🔗 Live Demo

> _Coming soon — deployment in progress._

---

## ✨ Features

- **Remote Queue Joining** — Customers join the waitlist from anywhere, no physical presence needed.
- **Live Queue Tracking** — Real-time position and ETA updates.
- **AI Wait Prediction** — Machine learning models predict table turnover accurately.
- **Restaurant Ops Dashboard** — Staff can view, call, and seat customers from a dedicated panel.
- **QR Code Entry** — Scan-to-join flow for in-restaurant onboarding.
- **Instant Notifications** — Customers get alerted when their table is ready.

---

## 🎨 Design Philosophy

The design combines **luxury restaurant aesthetics** with **modern SaaS product design**, inspired by brands like Apple, Linear, Stripe, and Uber.

| Principle | Implementation |
|---|---|
| **Premium Dark Theme** | Deep wood browns (`#16110D`, `#1B140F`, `#221812`) |
| **Glassmorphism** | `backdrop-filter: blur(24px)` with subtle glass borders |
| **Neon Accents** | Elegant amber glow (`#FF9D00`) — never cyberpunk |
| **Mobile-First** | Designed for 375px+ screens, sticky CTAs, full-screen nav drawer |
| **Typography** | Plus Jakarta Sans — large, comfortable, premium readability |

---

## 📁 Project Structure

```
SpotQ-Layout/
├── index.html            # Landing page (Hero, Features, Demo, CTA)
├── restaurant.html       # Restaurant Ops Dashboard
├── about.html            # About page (Mission, Values)
├── qr.html               # QR Code scan-to-join page
├── styles.css            # Shared premium stylesheet
├── README.md
└── assets/
    ├── SpotQ.jpeg         # Logo / Favicon
    ├── restaurant_bg.png  # Hero background image
    ├── restaurant_benefits.png  # Benefits section image
    ├── about_exciting.png # About page illustration
    └── qr_code.png        # QR code image
```

---

## 🚀 Getting Started

### Prerequisites

None — this is a pure static site (HTML, CSS, JavaScript). No build tools or dependencies required.

### Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SpotQ-Layout.git
   ```

2. Open `index.html` in your browser:
   ```bash
   # macOS
   open index.html

   # Windows
   start index.html

   # Or use VS Code Live Server extension
   ```

That's it. No `npm install`, no build step.

---

## 🌐 Deployment

This project can be deployed to any static hosting provider:

| Provider | Method |
|---|---|
| **Netlify** | Drag & drop the project folder |
| **Vercel** | Import from GitHub |
| **GitHub Pages** | Push to `main` branch, enable Pages |
| **Cloudflare Pages** | Connect GitHub repo |

### Quick Deploy (Netlify)

1. Go to [netlify.com](https://www.netlify.com/)
2. Click **Add new site** → **Deploy manually**
3. Drag & drop the `SpotQ-Layout` folder
4. Your site is live in seconds

---

## 📱 Pages Overview

### Landing Page (`index.html`)
The main marketing page featuring:
- Full-viewport hero with floating queue widget
- Problem statement section
- Interactive timeline (How It Works)
- Live queue demo with countdown simulation
- Bento grid feature showcase
- Restaurant benefits with premium imagery
- Testimonials carousel
- Final CTA with strongest glow effect

### Restaurant Ops (`restaurant.html`)
An operational dashboard for restaurant staff:
- Real-time stats overview (In Queue, Seated Today, Avg Wait)
- Interactive waitlist table
- Call Next / Seat Table actions with animations

### About (`about.html`)
Brand storytelling page:
- Mission statement with premium imagery
- Core values in bento grid layout

### QR Code (`qr.html`)
Scan-to-join flow for customers already at the restaurant.

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Structure | Semantic HTML5 |
| Styling | Vanilla CSS3 (CSS Variables, Grid, Flexbox) |
| Interactivity | Vanilla JavaScript (Intersection Observer, DOM) |
| Typography | [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) |
| Icons | Native emoji + inline SVGs |

---

## 📐 Design Tokens

```css
/* Backgrounds */
--bg-dark:    #16110D
--bg-medium:  #1B140F
--bg-light:   #221812

/* Accents */
--premium-amber:  #FF9D00
--luxury-gold:    #FFC247
--queue-green:    #00D084

/* Glassmorphism */
background:      rgba(255,255,255,0.06)
backdrop-filter:  blur(24px)
border:          1px solid rgba(255,255,255,0.12)
```

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is part of a group project at BroCamp.

---

<p align="center">
  <strong>SpotQ</strong> — Transform Restaurant Waiting Into A Better Experience.
</p>
