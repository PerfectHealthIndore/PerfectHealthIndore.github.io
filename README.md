# PerfectHealth.github.io
# 🌿 Dr. Vasundhara Sharma — Official Website
### Perfect Health Acupressure & Neuropathic Centre · Sampurna Gyan Jyotish Kendra

> A single-page holistic wellness website for Dr. Vasundhara Sharma, Indore — blending Acupressure, Naturopathy, and Vedic Astrology into one digital presence.

---

## 📸 Preview

![Hero Section](https://images.unsplash.com/photo-1506126613408-eca07ce68773?auto=format&fit=crop&w=1200&q=80)

---

## 🗂️ Project Structure

```
dr-vasundhara/
├── index.html          # Main website (all-in-one: HTML + CSS + JS)
├── index.php           # PHP version with contact form mail handler
└── README.md           # You are here
```

---

## ✨ Features

- **Single-page scroll** — Hero → About → Services → Astrology → Pricing → Testimonials → Contact
- **Sticky navbar** — transparent on top, deep-red on scroll, mobile hamburger menu
- **Health Centre section** — Chronic diseases, Pain management, Women's wellness
- **Jyotish Kendra section** — Kundali reading, Hastrekha, Vastu, Life guidance
- **Pricing cards** with strikethrough discounts and direct WhatsApp booking links
- **Contact form** with JS validation (no page reload)
- **WhatsApp floating button** with CSS pulse/ripple animation — always visible
- **Scroll-reveal animations** via IntersectionObserver
- **Fully responsive** — mobile-first, tested from 375px to 1440px
- **Bilingual** — English + Hindi (Devanagari script) throughout

---

## 💰 Pricing (Current Offers)

| Service | Original | Discounted |
|---|---|---|
| Kundali Reading | ~~₹750~~ | **₹500** |
| Hastrekha (Palm Reading) | ~~₹1000~~ | **₹750** |
| Kundali + Hastrekha Combo | ~~₹1000~~ | **₹750** |
| Acupressure Full Session | ~~₹1000~~ | **₹500** |

All "Book Now" buttons open WhatsApp with a pre-filled message for that specific service.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 (semantic) |
| Styling | CSS3 (custom properties, flexbox, grid, animations) |
| Scripting | Vanilla JavaScript (ES6+) |
| Icons | Font Awesome 6.4 CDN |
| Fonts | Google Fonts — Tiro Devanagari Hindi + Lato |
| Images | Unsplash (CDN, no download needed) |
| Mail (PHP ver.) | PHP `mail()` function |

**No frameworks. No jQuery. No Bootstrap. Pure HTML/CSS/JS.**

---

## 🚀 Getting Started

### Static Version (HTML only)

Just open `index.html` in any browser — no server needed.

```bash
git clone https://github.com/YOUR_USERNAME/dr-vasundhara.git
cd dr-vasundhara
open index.html
```

### PHP Version (with contact form)

Requires a PHP-enabled web server (Apache/Nginx + PHP 7+).

```bash
# Upload to your hosting via FTP or cPanel File Manager
# Place index.php in public_html/
# Make sure PHP mail() is enabled on your host
```

> **Note:** Most shared hosting (Hostinger, GoDaddy, Bluehost) supports `mail()` out of the box. For better deliverability, consider replacing `mail()` with PHPMailer + Gmail SMTP.

---

## 📱 WhatsApp Integration

The site uses direct WhatsApp deep links (`wa.me`) throughout:

- **Floating button** — always visible, bottom-right, with pulse animation
- **Hero CTA** — "Chat on WhatsApp" button
- **Each pricing card** — pre-filled message with service name and price
- **Contact section** — dedicated "Message on WhatsApp" block

WhatsApp number: `+91 79748-81571`

To update the number, find and replace `917974881571` across the file.

---

## 🎨 Color Palette

```css
--saffron:  #FF6B00   /* Buttons, accents, icons */
--deep-red: #8B0000   /* Headers, navbar, footer */
--gold:     #FFD700   /* Badges, card borders     */
--cream:    #FFFDF5   /* Page background           */
--dark:     #2d2d2d   /* Body text                 */
```

---

## 📞 Contact Details (Live Site)

| | |
|---|---|
| 📱 WhatsApp | [79748-81571](https://wa.me/917974881571) |
| 📧 Email | vasundhradr09@gmail.com |
| 📍 Location | Indore, Madhya Pradesh, India |

---

## 🤝 Credits

- **Design & Development** — Built with guidance from Claude (Anthropic)
- **Stock Images** — [Unsplash](https://unsplash.com) (free to use)
- **Icons** — [Font Awesome](https://fontawesome.com)
- **Fonts** — [Google Fonts](https://fonts.google.com)

---

## 📄 License

This project is proprietary. All content, branding, and copy belongs to **Dr. Vasundhara Sharma**. Do not reuse without permission.

---

<p align="center">Made with ❤️ for holistic wellness · Indore, MP · 2026</p>
