# 🕊️ Digital Wedding Card (Anis & Ariff)

A premium, single-page, static digital wedding invitation card built with a modern minimalist aesthetic, mobile-first design, and interactive details.

---

## 🎨 Design System & Aesthetics

### Theme: Modern Minimalist (Blueish White, Gold & Floral)
The visual layout uses **glassmorphism** (semi-transparent blurred overlays), clean typography, and delicate floral highlights.

*   **Color Palette (Controlled via CSS Variables)**:
    *   `--primary-bg`: Blueish White (`#xxxxxx` / `#xxxxxx` gradient)
    *   `--surface-card`: Translucent xxx (`rgba(xxx, xxx, xxx, 0.xx)` with `backdrop-filter: blur(10px)`)
    *   `--accent-gold`: Classic Gold (`#D4AF37` / `#C5A059`) for headings, borders, and buttons
    *   `--text-navy`: Midnight Blue/Navy (`#1B2A4A`) for readable text
*   **Typography**:
    *   `--font-cursive`: Playfair Display / Great Vibes (via Google Fonts)
    *   `--font-sans`: Inter / Montserrat for clean, high-readability details
*   **Deco elements**: Elegant white floral roses as floating background accents and frame ornaments.

### 🔄 Future Theme Switching
To answer the question about future customization, the design is structured around **CSS Custom Properties (Variables)** at the top of [style.css](file:///d:/Projects/kadkahwin/style.css). Changing the theme in the future is as easy as:
1.  Changing the color hex variables and font links in [style.css](file:///d:/Projects/kadkahwin/style.css).
2.  Replacing the background image asset files (`floral_bg.png` or `cover_bg.png`) in the `/assets/images/` directory with the new design's assets.
No structural HTML edits will be required.

---