# Maxwell Changilwa Campaign Website
## MCA Aspirant — Kabiro Ward, Nairobi County | 2027

---

## 📁 Project Structure

```
changilwa-campaign/
├── index.html              ← Homepage (Hero, Challenges, Vision, Manifesto Preview)
├── about.html              ← Biography, Timeline, Achievements
├── manifesto.html          ← Full 10-Pillar Manifesto
├── mjengo-workers.html     ← Workers Advocacy Page
├── projects.html           ← Development Projects with Progress Bars
├── gallery.html            ← Masonry Gallery with Lightbox
├── news.html               ← Blog/News with Search & Sidebar
├── contact.html            ← Contact Form, Map, WhatsApp
├── volunteer.html          ← Volunteer Registration Form
├── donate.html             ← Paystack Donations + M-Pesa + Multi-Currency
│
├── css/
│   └── main.css            ← Full design system (variables, components, animations)
│
└── js/
    ├── main.js             ← Core JS (navbar, scroll reveal, counters, typing, lightbox)
    └── donate.js           ← Donation logic (Paystack, currency conversion, M-Pesa)
```

---

## 🚀 Quick Setup

### 1. Open Locally
Simply open `index.html` in any modern browser — no build tools needed.

### 2. Paystack Integration
In `donate.html`, replace the Paystack public key:
```js
key: 'pk_test_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx',
// Replace with your live key: pk_live_XXXXXX
```
Get your key at: https://dashboard.paystack.com/#/settings/developer

### 3. WhatsApp Integration
Replace all instances of `254700000000` with your actual WhatsApp number (in international format, no `+`).

### 4. Google Maps
In `contact.html`, replace the Maps embed URL with your actual campaign office location.

### 5. Email
Replace all `info@changilwa2027.ke` references with your real campaign email.

---

## 🎨 Design System

### Colors
| Name | Hex |
|------|-----|
| Deep Green | `#0a4f2a` |
| Dark Green | `#052918` |
| Gold | `#c9a227` |
| Gold Light | `#e4bc4a` |
| Charcoal | `#1a1a1a` |
| White | `#ffffff` |

### Fonts (Google Fonts)
- **Montserrat** — Headings & Logo
- **Poppins** — Body text & UI
- **Inter** — Labels, meta, accents

### CSS Variables
All design tokens are in `css/main.css` under `:root { }` — easy to customize.

---

## ✨ Features

| Feature | Status |
|---------|--------|
| Responsive Mobile-First Design | ✅ |
| Sticky Animated Navbar | ✅ |
| Hero with Typing Animation | ✅ |
| Scroll Reveal Animations | ✅ |
| Animated Counters | ✅ |
| Glassmorphism Cards | ✅ |
| Masonry Gallery + Lightbox | ✅ |
| News Search + Sidebar | ✅ |
| Paystack Payment Integration | ✅ |
| M-Pesa STK Push | ✅ |
| Bank Transfer Details | ✅ |
| Multi-Currency (KES/USD/EUR/GBP/UGX/TZS) | ✅ |
| Real-Time Currency Conversion | ✅ |
| Project Filter Tabs | ✅ |
| Progress Bars (animated) | ✅ |
| Volunteer Skills Selector | ✅ |
| Contact Form + Google Maps | ✅ |
| Floating WhatsApp Button | ✅ |
| Scroll-to-Top Button | ✅ |
| Toast Notifications | ✅ |
| Success Overlays | ✅ |
| Mobile Menu Animation | ✅ |
| SEO Meta Tags | ✅ |
| Page Transitions | ✅ |

---

## 💳 Supported Currencies

| Currency | Symbol | Flag |
|----------|--------|------|
| KES | KES | 🇰🇪 |
| USD | $ | 🇺🇸 |
| EUR | € | 🇪🇺 |
| GBP | £ | 🇬🇧 |
| UGX | UGX | 🇺🇬 |
| TZS | TZS | 🇹🇿 |

> Exchange rates in `js/donate.js` — update periodically or integrate a live rates API.

---

## 📱 Browser Compatibility
- Chrome 80+ ✅
- Firefox 75+ ✅
- Safari 13+ ✅
- Edge 80+ ✅
- Mobile Chrome/Safari ✅

---

## 📞 Campaign Contact
- **Phone:** +254 700 000 000
- **Email:** info@changilwa2027.ke
- **Location:** Kabiro Ward, Westlands, Nairobi
- **WhatsApp:** https://wa.me/254700000000

---

*Built with HTML5, CSS3 & Vanilla JavaScript only. No frameworks. No dependencies.*
*© 2025 Maxwell Changilwa Campaign — Kabiro Ward, Nairobi*
