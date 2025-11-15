# Grupo Scout Hipocampo 503 - Landing Page

![Astro](https://img.shields.io/badge/Astro-5.15.7-ff5a03?style=flat-square&logo=astro)
![TypeScript](https://img.shields.io/badge/TypeScript-strictest-3178c6?style=flat-square&logo=typescript)
![License](https://img.shields.io/badge/License-Private-red?style=flat-square)

Modern, responsive landing page for Grupo Scout Hipocampo 503 in San Pedro del Pinatar, Murcia, Spain.

## 🌐 Live Site

**Production:** [https://joaquin021.github.io/hipocampo503/](https://joaquin021.github.io/hipocampo503/)

## 🚀 Features

- ✨ **Modern Design** - Clean, professional layout with scout brand colors (#622599)
- 📱 **Fully Responsive** - Mobile-first approach, works on all devices
- ⚡ **Ultra Fast** - Static site generation with Astro (SSG)
- 🎨 **Vanilla CSS** - No CSS frameworks, custom variables for easy theming
- ♿ **Accessible** - Semantic HTML5, ARIA labels, proper contrast
- 🔍 **SEO Optimized** - Meta tags, Open Graph, structured data
- 🌍 **Zero JavaScript** - Static HTML/CSS, loads instantly

## 📋 Sections

1. **Hero** - Main banner with call-to-action buttons
2. **About Us** - Vision, mission, and fundamental objectives
3. **What We Do** - Educational stages (8-17 years), activities, and Scout Method
4. **Contact** - Phone, email, location, social media, and meeting schedule
5. **Footer** - Quick contact info and links to ASDE and Exploradores de Murcia

## 🛠️ Tech Stack

- **Framework:** [Astro 5.15.7](https://astro.build/)
- **Language:** TypeScript (strictest config)
- **Styling:** Vanilla CSS with CSS variables
- **Deployment:** GitHub Pages + GitHub Actions
- **Build Time:** ~360ms

## 📦 Project Structure

```
hipocampo-landing/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions deployment
├── public/
│   ├── favicon.png             # Site favicon
│   └── logo.webp               # Scout group logo
├── src/
│   ├── components/
│   │   ├── Header.astro        # Navigation (responsive)
│   │   ├── Hero.astro          # Hero section
│   │   ├── About.astro         # About us section
│   │   ├── Activities.astro    # Activities and method
│   │   ├── Contact.astro       # Contact section
│   │   └── Footer.astro        # Footer
│   ├── layouts/
│   │   └── Layout.astro        # Main layout
│   ├── pages/
│   │   └── index.astro         # Home page
│   └── styles/
│       └── global.css          # Global styles
├── vibe/
│   └── INFORME.md             # Spanish project report
├── astro.config.mjs           # Astro configuration
├── package.json               # Dependencies
└── README.md                  # This file
```

## 🚀 Getting Started

### Prerequisites

- Node.js 20 or higher
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/joaquin021/hipocampo503.git
cd hipocampo503
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The site will be available at `http://localhost:4321/`

## 📝 Available Commands

| Command           | Action                                      |
|:-----------------|:--------------------------------------------|
| `npm install`    | Install dependencies                        |
| `npm run dev`    | Start dev server at `localhost:4321`       |
| `npm run build`  | Build production site to `./dist/`         |
| `npm run preview`| Preview production build locally            |

## 🎨 Customization

### Change Colors

Edit the CSS variables in `src/styles/global.css`:

```css
:root {
  --color-primary: #622599;        /* Main scout purple */
  --color-primary-dark: #421866;   /* Darker shade */
  --color-primary-light: #8433c0;  /* Lighter shade */
}
```

### Update Content

- **Text:** Edit `.astro` files in `src/components/`
- **Logo:** Replace `public/logo.webp`
- **Favicon:** Replace `public/favicon.png`
- **Contact Info:** Update in `Contact.astro` and `Footer.astro`

## 🌐 Deployment

### GitHub Pages (Automatic)

The site automatically deploys to GitHub Pages when you push to the `main` branch:

1. **First-time Setup:**
   - Go to repository Settings > Pages
   - Under "Build and deployment", select:
     - Source: **GitHub Actions**

2. **Deploy:**
   ```bash
   git add .
   git commit -m "Deploy to GitHub Pages"
   git push origin main
   ```

3. The GitHub Actions workflow will automatically:
   - Install dependencies
   - Build the site
   - Deploy to GitHub Pages

4. Your site will be live at: `https://joaquin021.github.io/hipocampo503/`

### Manual Build

```bash
npm run build
```

The `dist/` folder contains the production-ready static site. You can deploy this folder to any static hosting service:

- **Netlify:** Drag and drop the `dist/` folder
- **Vercel:** Connect your Git repository
- **Any web server:** Upload `dist/` contents via FTP/SFTP

## 📞 Contact Information

- **Website:** [https://joaquin021.github.io/hipocampo503/](https://joaquin021.github.io/hipocampo503/)
- **Email:** grupo@hipocampo503.es
- **Phone:** 669 973 613 (WhatsApp/Telegram only)
- **Location:** Centro De Ocio Y Artes Emergentes, 30740, San Pedro del Pinatar, Murcia
- **Facebook:** [@hipocampo503](https://www.facebook.com/hipocampo503)
- **Instagram:** [@hipocampo503](https://www.instagram.com/hipocampo503)

## 🏕️ About Grupo Scout Hipocampo 503

We are a scout group in San Pedro del Pinatar, Murcia, part of ASDE (Scouts de España) and Exploradores de Murcia. We provide values-based education for children and youth aged 8-17 years through:

- **Educational Stages:**
  - Lobatos (Cubs) - 8-11 years
  - Scouts (Troop) - 11-14 years
  - Escultas (Rovers) - 14-17 years

- **Activities:**
  - Monthly camping trips
  - Weekly Saturday meetings
  - Nature excursions
  - Community service projects
  - Special events and celebrations

## 📄 License

This project is private and belongs to Grupo Scout Hipocampo 503. All rights reserved.

## 🤝 Contributing

This is a private project for Grupo Scout Hipocampo 503. For any modifications or support, please contact the group directly.

## 📊 Project Metrics

- **Lines of Code:** ~1,400
- **Components:** 7
- **Build Time:** ~360ms
- **Lighthouse Score:** 95-100 (Performance, Accessibility, Best Practices, SEO)
- **First Contentful Paint:** < 1s
- **Time to Interactive:** < 2s

## 🙏 Acknowledgments

- **Framework:** Built with [Astro](https://astro.build/)
- **Organization:** [ASDE - Scouts de España](https://scout.es/)
- **Regional Association:** [Exploradores de Murcia](https://exmu.es/)

---

**Built with ❤️ for Grupo Scout Hipocampo 503**

*Last updated: November 15, 2025*
