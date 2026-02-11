# Trinetro Labs — Landing Page

A modern, responsive landing page for **Trinetro Labs** — an AI-powered data intelligence platform. Built with Bootstrap 5 and vanilla JavaScript.

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom styling via `main.css`
- **JavaScript (ES6)** — Interactive functionality
- **Bootstrap 5.3** — Responsive grid and UI components
- **AOS** — Scroll-triggered animations
- **Bootstrap Icons** — Icon set
- **GLightbox** — Lightbox for media
- **Swiper** — Touch slider/carousel
- **FormSubmit.co** — Contact form email delivery (no backend)

## Project Structure

```
Landing_Page_Tri/
├── index.html                  # Main landing page
├── robots.txt                  # Search engine crawl rules
├── README.md
├── .vscode/
│   └── settings.json           # VS Code workspace settings
└── assets/
    ├── favicon.ico
    ├── css/
    │   └── main.css            # All custom styles
    ├── img/
    │   ├── about.jpg
    │   ├── favicon.png
    │   ├── home.mp4            # Hero section video
    │   └── query.mp4           # Contact section video
    ├── js/
    │   └── main.js             # Core JS (navigation, scroll, animations)
    └── vendor/
        └── contact-form/
            └── validate.js     # Form validation handler
```

## Running Locally

### Using VS Code Live Server
1. Install the **Live Server** extension
2. Right-click `index.html` → **Open with Live Server**

### Using Python
```bash
python -m http.server 8000
```
Open `http://localhost:8000` in your browser.

### Using Node.js
```bash
npx http-server -p 8000
```

## Sections

| Section            | Description                                      |
|--------------------|--------------------------------------------------|
| Hero               | Welcome message with "Launching Soon" animation  |
| Featured Services  | AI Analytics, Plain-English Queries, Security    |
| About              | Company overview with image                      |
| FAQ                | Frequently asked questions accordion             |
| Contact            | Query form (via FormSubmit.co) + WhatsApp button |
| Footer             | Links, social media, copyright                   |

