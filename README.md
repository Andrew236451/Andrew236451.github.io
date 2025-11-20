# 🚀 Andrew's Developer Portfolio - Open Source Template

> Un portfolio moderno, minimalista e completamente responsivo per developer. Perfetto per GitHub Pages. **Template gratuito e open source!**

[![GitHub Stars](https://img.shields.io/github/stars/Andrew236451/portfolio?style=social)](https://github.com/Andrew236451/portfolio)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Made with Love](https://img.shields.io/badge/made%20with-❤️-red)](https://github.com/Andrew236451)

---

## 📸 Demo Live

Visita il portfolio: **[andrew236451.github.io](https://andrew236451.github.io)**

---

## ✨ Features Principali

### 🎨 Grafica Moderna & Minimalista
- ✅ **Canvas Particle System** - Particelle dinamiche animate
- ✅ **Blob Animations** - Background con blob galleggianti
- ✅ **Floating Cards 3D** - Card che fluttuano
- ✅ **Glassmorphism Effects** - Effetto vetro trasparente
- ✅ **Gradient Backgrounds** - Sfondi sfumati eleganti
- ✅ **Smooth 60 FPS Animations** - Transizioni fluide

### 💻 Perfetto per Developer
- ✅ **Font JetBrains Mono** - Monospace professionale
- ✅ **Font Outfit** - Display font moderno
- ✅ **Code Editor Mockup** - Simulazione VSCode realistico
- ✅ **Code Blocks** - Syntax highlighting colorato
- ✅ **Typing Effect** - Effetto macchina da scrivere
- ✅ **Tech Stack Grid** - Showcase tecnologie

### 📱 100% Responsivo
- ✅ **Mobile First** - Design pensato per mobile
- ✅ **3 Breakpoint** - Desktop, Tablet, Mobile
- ✅ **Touch Friendly** - Bottoni e link ottimizzati
- ✅ **Hamburger Menu** - Navigazione mobile elegante
- ✅ **Perfetto su ogni device** - Testato ovunque

### ⚡ Performance & SEO
- ✅ **Lightweight** - < 100KB totale
- ✅ **No Dependencies** - Vanilla HTML/CSS/JavaScript
- ✅ **Optimized Code** - Pulito e veloce
- ✅ **SEO Ready** - Meta tags e structured data
- ✅ **Accessibility** - WCAG compliant

### 🎯 Interattività Avanzata
- ✅ **Scroll Progress Bar** - Barra di avanzamento top
- ✅ **Intersection Observer** - Animazioni al scroll
- ✅ **Active Navigation** - Highlight sezione attiva
- ✅ **Counter Animation** - Numeri che contano
- ✅ **Ripple Effects** - Feedback sui bottoni
- ✅ **Parallax Effects** - Effetto depth

---

## 🚀 Quick Start (5 minuti)

### 1. Clone il Repository
```bash
git clone https://github.com/Andrew236451/portfolio.git
cd portfolio
```

### 2. Personalizza
Apri `index.html` e modifica:
- Nome e descrizione (cerca `typing-text`)
- Progetti nella sezione "Projects"
- Skills nella sezione "Skills"
- Link social nella sezione "Contact"

### 3. Testa in Locale
```bash
python3 -m http.server 8000
# Visita http://localhost:8000
```

### 4. Deploy su GitHub Pages
```bash
# Pubblica il repository
git add .
git commit -m "My portfolio"
git push origin main

# Abilita Pages:
# 1. Vai a Settings del repository
# 2. Seleziona "Pages"
# 3. Scegli "Deploy from main branch"
# 4. Salva
# 5. Disponibile in 1-2 minuti su:
#    https://tuousername.github.io/portfolio
```

✅ **Fatto! Il tuo portfolio è online!**

---

## 📁 Struttura del Progetto

```
portfolio/
├── index.html              # File principale (personalizza qui!)
├── styles.css              # Styling completo (modifica colori qui)
├── script.js               # JavaScript (non modificare)
├── package.json            # NPM config
├── LICENSE                 # MIT License
├── .gitignore              # Git ignore
├── README.md               # Questo file
└── .github/workflows/      # GitHub Actions (auto-deploy)
    └── deploy.yml
```

---

## 🎨 Customizzazione Rapida

### Cambiare il Titolo
In `index.html` trova:
```html
<span class="typing-text">👋 Hey there, I'm Andrew!</span>
```
Cambia "Andrew" con il tuo nome.

### Cambiare i Colori Principali
In `styles.css` modifica:
```css
:root {
    --primary-color: #7c3aed;      /* Viola */
    --secondary-color: #ec4899;    /* Rosa */
    --tertiary-color: #06b6d4;     /* Ciano */
}
```

### Aggiungere un Progetto
Copia una `project-card` in `index.html`:
```html
<div class="project-card">
    <div class="project-header">
        <div class="project-icon large">
            <i class="fas fa-ICONA"></i>
        </div>
        <div class="project-status">
            <span class="status-badge active">Status</span>
        </div>
    </div>
    <h3>Nome Progetto</h3>
    <p>Descrizione progetto...</p>
    <div class="project-tech">
        <span class="tech-badge">Tecnologia1</span>
        <span class="tech-badge">Tecnologia2</span>
    </div>
    <a href="link" class="project-link">Scopri di più →</a>
</div>
```

### Aggiungere una Skill
Copia una `skill-category` in `index.html`:
```html
<div class="skill-category">
    <div class="category-icon">
        <i class="fas fa-ICONA"></i>
    </div>
    <h3>Nome Skill</h3>
    <p class="category-desc">Descrizione...</p>
    <div class="skills-list">
        <div class="skill-item">
            <div class="skill-name">
                <span>Tecnologia</span>
                <span class="skill-percent">85%</span>
            </div>
            <div class="skill-bar">
                <div class="skill-progress" style="width: 85%"></div>
            </div>
        </div>
    </div>
</div>
```

---

## 🛠️ Customizzazione Avanzata

### Aggiungere una Nuova Sezione
```html
<section id="nuova-sezione" class="nuova-sezione">
    <div class="container">
        <h2 class="section-title">Titolo Sezione</h2>
        <!-- Contenuto -->
    </div>
</section>
```

Aggiungi il link nel menu:
```html
<li><a href="#nuova-sezione" class="nav-link">Nuova Sezione</a></li>
```

### Cambiare Font
I font sono importati da Google Fonts in `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;600;700&family=Outfit:wght@400;500;600;700;800&display=swap" rel="stylesheet">
```

### Aggiungere Dark Mode
Aggiungi in `styles.css`:
```css
@media (prefers-color-scheme: dark) {
    :root {
        --light-bg: #1a1a1a;
        --text-dark: #f0f0f0;
        --border-color: #333;
    }
}
```

---

## 📊 Sezioni Incluse

### 1. Navigation
- Sticky navbar con logo
- Link alle sezioni
- Mobile hamburger menu
- Active state highlight

### 2. Hero Section
- Canvas particle animation
- Typing effect
- Code blocks
- Code editor mockup
- Stats card animate
- Call-to-action buttons

### 3. About
- Floating cards 3D
- Code-style presentation
- Badge per qualità personali

### 4. Skills
- 4 categorie professionali
- Progress bars animate
- Tech stack icon grid

### 5. Projects
- 4 project cards
- Status badges
- Tech tags
- Hover effects

### 6. Goals
- Sezione motivazionale

### 7. Contact
- 3 social buttons (GitHub, Email, YouTube)

### 8. Footer
- Copyright info

---

## 🎨 Palette Colori

```
Primary:    #7c3aed  (Viola)      ■
Secondary:  #ec4899  (Rosa)       ■
Tertiary:   #06b6d4  (Ciano)      ■
Success:    #10b981  (Verde)      ■
Background: #f8fafc  (Grigio)     ■
Dark:       #0f172a  (Blu scuro)  ■
```

---

## 💻 Tecnologie Usate

- **HTML5** - Struttura semantica
- **CSS3** - Grid, Flexbox, Animations, Gradients
- **JavaScript Vanilla** - Canvas API, IntersectionObserver
- **Google Fonts** - JetBrains Mono, Outfit
- **Font Awesome 6.4** - Icons professionali

---

## 📱 Responsive Breakpoints

```css
Desktop:        1200px+     (Layout completo)
Tablet:         768px-1199px (2 colonne → 1)
Mobile:         <768px      (Ottimizzato)
Small Mobile:   <480px      (Ultra compact)
```

---

## 🚀 Deploy Options

### GitHub Pages ⭐ (Consigliato)
```bash
# Abilitare in: Settings → Pages → main branch
# Disponibile a: https://username.github.io/portfolio
```

### Netlify
```bash
# Trascina la cartella su netlify.com
# Pronto in 30 secondi!
```

### Vercel
```bash
npm install -g vercel
vercel
```

### Traditional Hosting
Carica i file via FTP/SFTP su qualsiasi host.

---

## 📊 Statistics

| Metrica | Valore |
|---------|--------|
| HTML Lines | 650+ |
| CSS Lines | 1100+ |
| JS Lines | 400+ |
| Total Size | < 100KB |
| Animations | 15+ |
| Browser Support | All modern |
| Lighthouse Score | 95+ |
| Mobile Ready | 100% |

---

## 🔧 Animazioni Disponibili

- `@keyframes float-blob-1/2/3` - Blob animations
- `@keyframes typing` - Typing effect
- `@keyframes slide-in-left` - Slide animation
- `@keyframes float-editor` - Editor floating
- `@keyframes float-card-1/2/3` - Card animations
- `@keyframes ripple` - Ripple effect
- Canvas Particle Animation - JavaScript

---

## 🐛 Troubleshooting

### Le animazioni non appaiono?
```bash
# Svuota cache e ricarica
Ctrl+Shift+Delete  # Cache clear
Ctrl+F5            # Force refresh
```

### GitHub Pages non funziona?
1. Assicurati che il repository sia **pubblico**
2. Abilita Pages nelle **Settings**
3. Aspetta 2-3 minuti
4. Verifica l'URL: `https://username.github.io/portfolio`

### Stile non cambia?
1. Salva il file (`Ctrl+S`)
2. Ricarica pagina (`Ctrl+Shift+R` per force refresh)
3. Svuota cache browser

### Porta 8000 già in uso?
```bash
lsof -i :8000
kill -9 <PID>
python3 -m http.server 8001  # Usa porta diversa
```

---

## 💡 Pro Tips

1. **Icons** - Trova più icone su [FontAwesome](https://fontawesome.com/icons)
2. **Colors** - Palette inspiration su [ColorHunt](https://colorhunt.co/)
3. **Images** - Comprimi con [TinyPNG](https://tinypng.com/)
4. **SEO** - Modifica meta tags per migliore ranking
5. **Analytics** - Aggiungi Google Analytics nel `<head>`
6. **Custom Domain** - Usa CNAME in Pages settings
7. **SSL/HTTPS** - GitHub Pages le fornisce gratis
8. **Auto-Update** - Basta fare push, Pages aggiorna

---

## 🎓 Come Estendere

### Aggiungere un Blog
```html
<section id="blog" class="blog">
    <h2 class="section-title">Blog</h2>
    <div class="blog-grid">
        <!-- Post cards -->
    </div>
</section>
```

### Aggiungere Certificazioni
```html
<div class="certification-card">
    <h3>Certificazione</h3>
    <p>Emesso da Organizzazione</p>
</div>
```

### Aggiungere Form Contatti
Usa [Formspree](https://formspree.io/) o [Netlify Forms](https://www.netlify.com/products/forms/).

---

## 🤝 Contribuire

Vuoi migliorare il template?

1. **Fork** il repository
2. Crea un branch (`git checkout -b feature/AmazingFeature`)
3. Commit (`git commit -m 'Add AmazingFeature'`)
4. Push (`git push origin feature/AmazingFeature`)
5. Apri una **Pull Request**

---

## 📝 Licenza

Questo progetto è open source sotto la licenza **MIT**.

**Sei libero di:**
- ✅ Usare il template gratuitamente
- ✅ Modificarlo
- ✅ Distribuirlo
- ✅ Usarlo commercialmente

---

## 🔗 Contatti & Link

- **GitHub**: [Andrew236451](https://github.com/Andrew236451)
- **YouTube**: [@Andrew_v2.0](https://www.youtube.com/@Andrew_v2.0)
- **Email**: andreaaziendale8@gmail.com

---

## 🎯 Checklist Personalizzazione

- [ ] Clone il repository
- [ ] Personalizza nome e descrizione
- [ ] Aggiungi tuoi progetti
- [ ] Aggiungi tue skills
- [ ] Modifica colori se desideri
- [ ] Testa in locale
- [ ] Pubblica su GitHub
- [ ] Abilita GitHub Pages
- [ ] Condividi il link

---

## 🎉 Ready?

```bash
# 1. Clone
git clone https://github.com/Andrew236451/portfolio.git

# 2. Personalizza
# Modifica index.html

# 3. Testa
python3 -m http.server 8000

# 4. Pubblica
git push origin main

# 5. Abilita Pages
# Settings → Pages → main branch

# 6. Condividi
# https://tuousername.github.io/portfolio
```

**Il tuo portfolio è pronto! Buona fortuna!** 🚀

---

<div align="center">

Made with ❤️ by [Andrew](https://github.com/Andrew236451)

MIT License | Open Source | GitHub Pages Ready

[⬆ Back to top](#-andrews-developer-portfolio---open-source-template)

</div>

