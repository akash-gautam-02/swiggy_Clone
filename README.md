# Swiggy Clone (Responsive Frontend)

A modern, responsive **Swiggy-inspired landing page clone** built using HTML, CSS, and Bootstrap. This project focuses on clean UI structure, mobile-first responsiveness, smooth section flow, and reusable styling for food-delivery style platforms.

## 🚀 Project Overview

This project replicates the core visual sections of a Swiggy-like homepage:

- Hero section with navbar and search controls
- Food category options
- Instamart grocery section
- Dineout restaurant cards
- App download banner
- Auto-scrolling city delivery sections

The latest update improves the layout to be **fully responsive across all major screen sizes** (desktop, laptop, tablet, and mobile).

---

## 🛠️ Tech Stack Used

- **HTML5** – semantic structure and sectioning
- **CSS3** – custom styling, media queries, animation
- **Bootstrap 5** – grid system, utility classes, responsive components
- **Bootstrap Icons** – iconography for navbar/search/actions
- **Google Fonts (Poppins)** – typography consistency

---

## ✅ What Was Improved for Responsiveness

To make the UI fully adaptive for every screen size, the following improvements were implemented:

1. **Fluid input/search layout**
   - Search controls now wrap and align properly on smaller devices.
   - Widths changed from rigid percentages to flexible `min()` based sizing.

2. **Hero section scaling**
   - Hero card heights and heading font sizes now scale with breakpoints.
   - Side decorative images are hidden on smaller screens to avoid overlap.

3. **Navbar mobile behavior**
   - Navigation links and action buttons are stacked vertically on tablet/mobile.
   - Better spacing and readability when collapsed.

4. **Scrollable card rows on smaller screens**
   - Hero cards and Instamart cards become horizontal scroll rows for compact devices.
   - Preserves design quality without shrinking content excessively.

5. **City buttons readability improvements**
   - Better padding, border, and text wrapping.
   - Improved touch-target size for mobile interaction.

6. **Fine-grained media breakpoints**
   - Added responsive rules for:
     - `<1200px`
     - `<992px`
     - `<768px`
     - `<576px`

---

## 📁 Project Structure

```text
swiggy_Clone/
├── index.html
├── README.md
├── css/
│   ├── style.css
│   ├── variable.css
│   └── responisve.css
└── images/
```

---

## ▶️ How to Run

Because this is a static frontend project, you can run it in multiple ways:

### Option 1: Open directly
Open `index.html` in any browser.

### Option 2: Run via local server (recommended)
Use VS Code Live Server or:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## 🔮 Future Enhancements Planned

The following features can be added next to make the project production-like:

- Backend API integration for dynamic restaurant/food data
- Real search and location auto-suggest
- Authentication pages (Sign in / Sign up)
- Cart flow and checkout UI
- Dark mode toggle
- Accessibility audit (ARIA improvements + keyboard navigation)
- Performance optimization (image compression + lazy loading strategy)
- PWA support for installable app experience

---

## 💡 Learning Outcomes

This project demonstrates:

- How to combine Bootstrap with custom CSS for design control
- How to convert fixed desktop UI into a truly responsive layout
- How to optimize UX for small screens without breaking desktop look
- Practical use of modern CSS units and media query strategy

---

## 👨‍💻 Author Note

This clone is made for frontend practice and UI engineering learning. Brand assets and naming belong to their respective owners.

