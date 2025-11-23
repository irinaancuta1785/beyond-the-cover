A community-driven platform that brings readers together to discover and discuss books they love.

# 📚 Beyond the cover

## 🧩 Project Overview
Beyond The Cover is a single-page book club site for my first year project. It uses HTML, CSS, and Bootstrap 5 with no custom JavaScript. Booking flows are handled with CSS-only modals and a simple confirmation toast so the site stays fully static and easy to deploy on GitHub Pages.

## 🎯 Core Features
- Fixed navbar (collapses on small screens) linking to Home, Join a book club, Testimonials, FAQ, and Contact.
- Hero banner with a quote plus a discussion guide explaining how sessions run.
- Grid of six December 2025 book discussions with cover art, descriptions, pricing, and "Book Your Spot" triggers.
- Monthly pass banner and modal covering all six sessions.
- CSS `:target` modals for each booking and a confirmation toast anchor.
- Testimonials cards and a Bootstrap accordion FAQ.
- Footer with contact details and social links that open in a new tab using `rel="noopener noreferrer"`.

## 🎨 Design Choices

### Color Palette
Warm, bookish tones to keep the page cozy and legible.

| Color Name | Hex Code | Where It's Used |
|-------|----------|----------|
| Cream | #f5e6d3 | Book card backgrounds |
| Light Brown | #e8d5b7 | Card gradients |
| Medium Brown | #8b6f47 | Author names, buttons |
| Dark Brown | #6b5537 | Button hover states |
| Very Dark Brown | #3d2817 | Primary text, monthly pass button |
| Dark Background | #2c2416 | Section backgrounds |
| Tan/Beige | #d4c4a8 | Subtitle text |
| Golden Brown | #c9a961 | Monthly pass banner |
| Saddle Brown | #b8935a | Banner gradient middle |
| Sienna | #a67c52 | Banner gradient darker part |

### Typography
- Headings and highlighted text: Georgia (Times New Roman fallback) for a classic, bookish feel.
- Body text and UI: System font stack for fast, clean rendering.
- Book titles are bold; author names italicized to separate them from descriptions.

### Imagery
- Hero and card images are sourced from free stock sites (Pexels/Unsplash) and include descriptive `alt` text.
- Six book covers plus a hero background; all stored locally under `assets/images/`.

## 🧰 Tech Stack

| Technology | Purpose |
|-------------|----------|
| HTML5 | Page structure |
| CSS3 | Custom styling and CSS-only modals/toast |
| Bootstrap 5 (CSS & JS via CDN) | Grid, navbar collapse, accordion, base styles |
| Font Awesome | Social icons |
| Git & GitHub | Version control and hosting |
| VS Code / Sourcetree | Local development workflow |
| GitHub Pages | Deployment |

## 🧭 Testing

### Code Validation
- **HTML:** W3C HTML Validator (see `assets/images/screenshots/html-validation.png`). No errors after fixing the duplicate `h1` and trailing slashes.
- **CSS:** W3C Jigsaw Validator (see `assets/images/screenshots/css-validation.png`). No errors; expected warnings for the `-apple-system` font stack.

### Responsiveness
- Manually checked in Chrome (macOS) and Safari (macOS).
- Chrome DevTools device emulation for iPhone 14 Pro to confirm the grid shifts 3 -> 2 -> 1 columns, navbar collapse works, and hero text remains readable.

### Browser Compatibility
- Manually verified on Chrome (macOS) and Safari (macOS/iOS).

### Functionality Checks
- Navbar links scroll smoothly to their sections; the mobile toggle opens/closes correctly.
- All six "Book Your Spot" buttons and the monthly pass CTA open the matching CSS modal; close via x or Cancel.
- Booking forms use HTML5 required, email, and tel validation; submission lands on the confirmation toast anchor.
- FAQ accordion expands/collapses via the Bootstrap bundle.
- Social links open in a new tab with `rel="noopener noreferrer"`.

### Accessibility
- Semantic structure with a single `h1` in the hero, `h2` for sections, and `h3` for cards/modals.
- Descriptive `alt` text on the hero image and all six book covers.
- Keyboard focusable nav, buttons, links, and form controls; visible focus outlines remain.
- Color contrast (computed):
  - `#3d2817` on `#f5e6d3`: 11.32:1
  - `#ffffff` on `#6b5537`: 7.05:1
  - `#ffffff` on `#2c2416`: 15.32:1

### Known Issues
- None identified in current testing.

## 📦 Performance and Assets
- Static assets only: `index.html` (~42 KB) and custom CSS (~13.8 KB).
- External dependencies via CDN: Bootstrap 5 bundle and Font Awesome icons.
- No custom JavaScript; interactivity is handled by CSS and Bootstrap components.

## ⚙️ Deployment

### Live Site
- https://irinaancuta1785.github.io/beyond-the-cover/

### Repository
- https://github.com/irinaancuta1785/beyond-the-cover

### Deploying to GitHub Pages
1. Commit and push all changes to the `main` branch.
2. In GitHub, open **Settings → Pages**.
3. Set **Source** to `main` and **Folder** to `/ (root)`, then save.
4. Wait for the publish message and verify the live link.

## 🛠️ Local Development
1. Clone the repo and `cd` into it:
   ```bash
   git clone https://github.com/irinaancuta1785/beyond-the-cover.git
   cd beyond-the-cover
   ```
2. Open `index.html` directly in a browser, or use VS Code Live Server for auto-reload.
3. Optional local servers:
   ```bash
   python3 -m http.server 8000
   # or
   npm install -g http-server
   http-server
   ```

## 📁 Project Structure
```
beyond-the-cover/
├── index.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── images/
│       ├── books_presentation.jpg
│       ├── books-logo.jpg
│       ├── kane_and_abel.jpeg
│       ├── nostre_damme_de_paris.jpeg
│       ├── les_miserables_victor_hugo.jpeg
│       ├── tolstoi_anna_karenine.jpeg
│       ├── shogun_james_clavell.jpeg
│       ├── journey_to_the_center_of_the_earth.jpeg
│       └── screenshots/
│           ├── html-validation.png
│           └── css-validation.png
└── README.md
```

## 🧾 Credits and Attribution
- Code and content by **Irina Ancuta**.
- Images from [Pexels](https://pexels.com), [Unsplash](https://unsplash.com), and [Pinterest](https://pinterest.com).
- Icons from [Font Awesome](https://fontawesome.com).
- Bootstrap framework from [getbootstrap.com](https://getbootstrap.com).

## 🏁 Acknowledgements
- Thanks to **Code Institute** for guidance and assessment materials.
- Inspiration from book club communities such as Goodreads and local reading circles.
