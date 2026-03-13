# Remake Kingdom Website

Welkom bij de Remake Kingdom Minecraft Server website met **modern, ultra-strak design**!

## 📁 Bestanden

- `index.html` - Homepage met server informatie
- `regels.html` - Server regels pagina
- `staff.html` - Staff team overzicht
- `webshop.html` - Webshop redirect pagina
- `styles.css` - Ultra modern styling voor alle pagina's
- `config.js` - Configuratie bestand (belangrijk!)
- `assets/` - Map voor afbeeldingen (inclusief logo)

## 🎨 Modern Design Thema

De website heeft een **cutting-edge modern design** met:
- **Kleuren**: Indigo (#6366f1), Purple (#8b5cf6), Pink (#ec4899) gradient thema
- **Glassmorphism**: Frosted glass effect met blur en transparantie  
- **Lettertypen**: Inter (body) en Poppins (headings) voor modern gevoel
- **Effecten**: Smooth animaties, gradient borders, glow effects
- **Sfeer**: Donkere achtergrond met neon accenten en futuristische uitstraling
- **Responsive**: Perfect op desktop, tablet én mobile

## ✨ Design Features

### 🔮 Glassmorphism Cards
- Transparante cards met backdrop blur
- Gradient borders die oplichten bij hover
- Smooth transform animaties
- Light reflection effects

### 🌈 Gradient Accenten
- Multi-color gradient primary (indigo → purple → pink)
- Animated background gradients
- Text gradient effects op titels
- Custom scrollbar met gradient

### ⚡ Interactieve Effecten
- Buttery smooth hover animaties
- Scale & lift effecten
- Modern notification systeem
- Pulse animations op speciale elementen

### 📱 Volledig Responsive
- Mobile-first design
- Flexible grid layouts
- Touch-friendly buttons
- Optimized voor alle schermgroottes

## 🖼️ **BELANGRIJK: Afbeeldingen Toevoegen**

### Logo Toevoegen
1. Sla je RKD logo op als `logo.png` in de `assets/` map
2. Het logo moet een PNG zijn (transparante achtergrond werkt het beste)
3. Aanbevolen breedte: 80-150px

Het logo wordt automatisch getoond in de navigatiebalk op alle pagina's met moderne glow effecten.

### Achtergrond Afbeelding Toevoegen (NIEUW!)
1. Sla je **Minecraft world screenshot** op als `rkd-background.jpg` in de `assets/` map
2. Aanbevolen formaat: **1920x1080 pixels of hoger** voor hoogste kwaliteit
3. Deze achtergrond wordt gebruikt op alle hero secties (homepage + subpagina's)
4. **Tip**: Gebruik een mooie screenshot van je server world voor de beste uitstraling!

### Beheer/Owner Hoofd Toevoegen
### Beheer/Owner Hoofd Toevoegen
1. Sla de Minecraft skin afbeelding op als `owner-head.png` in de `assets/` map
2. Je kunt ook een Minecraft avatar downloaden van:
   - `https://mc-heads.net/avatar/SPELERNAAM`
   - `https://crafatar.com/avatars/UUID`
3. Of gebruik je eigen Minecraft skin screenshot

De afbeelding wordt automatisch getoond op de Staff pagina als Beheer.

## �🔧 Configuratie

### Webshop Link Aanpassen

Open `config.js` en pas de volgende regel aan:

```javascript
const WEBSHOP_URL = 'https://jouw-webshop-link.nl';
```

Vervang `'https://jouw-webshop-link.nl'` met je eigen webshop URL.

### Server IP Aanpassen

Open `index.html` en zoek naar:

```html
<div class="server-ip" onclick="copyIP()">
    play.remakekingdom.nl
</div>
```

En ook in het script gedeelte:

```javascript
const ip = 'play.remakekingdom.nl';
```

Vervang beide met je eigen server IP.

### Staff Leden Aanpassen

Open `staff.html` en pas de staff member kaarten aan:

```html
<div class="staff-member fade-in">
    <div class="staff-avatar">
        <img src="URL_NAAR_AVATAR" alt="Naam">
    </div>
    <div class="staff-role">🔴 Admin</div>
    <div class="staff-name">Naam</div>
    <div class="staff-description">Beschrijving</div>
</div>
```

Je kunt Minecraft avatar URLs gebruiken zoals:
- `https://mc-heads.net/avatar/SPELERNAAM`
- `https://crafatar.com/avatars/UUID`

### Server Regels Aanpassen

Open `regels.html` en pas de regels aan in de `<ul class="rules-list">` sectie.

## 🎨 Kleuren Aanpassen

Open `styles.css` en pas de CSS variabelen aan bovenaan het bestand:

```css
:root {
    --primary-color: #6366f1;      /* Indigo - primary accent */
    --secondary-color: #8b5cf6;     /* Purple - secondary accent */
    --accent-color: #ec4899;       /* Pink - extra accent */
    --success-color: #10b981;      /* Green - success states */
    --dark-bg: #0f172a;            /* Dark blue background */
    --darker-bg: #020617;          /* Deepest background */
    --card-bg: rgba(30, 41, 59, 0.5);  /* Card background */
    --text-color: #f1f5f9;         /* Light text */
    --text-secondary: #cbd5e1;     /* Secondary text */
}
```

### 🌈 Gradients
De site gebruikt verschillende gradients:
- `--gradient-primary`: Indigo → Purple → Pink (main gradient)
- `--gradient-1`: Purple gradient voor accenten
- `--gradient-2`: Pink gradient voor highlights
- `--gradient-3`: Cyan gradient voor speciale effecten

### 📝 Moderne Lettertypen
De site gebruikt twee Google Fonts:
- **Inter**: Voor body text en UI elementen (clean, modern sans-serif)
- **Poppins**: Voor headings en belangrijke tekst (geometric, bold sans-serif)

Je kunt deze lettertypen aanpassen in de `@import` regel in `styles.css`.

## 🚀 Website Gebruiken

1. **Lokaal testen**: Open `index.html` in je browser
2. **Online zetten**: 
   - Upload alle bestanden naar je webhosting
   - Of gebruik GitHub Pages (gratis)
   - Of gebruik services zoals Netlify, Vercel (gratis)

### GitHub Pages Gebruiken

1. Push alle bestanden naar je GitHub repository
2. Ga naar Repository Settings > Pages
3. Selecteer de branch (meestal `main`)
4. Je website is nu beschikbaar op `https://jouwgebruikersnaam.github.io/RKDSite`

## 📱 Responsive Design

De website is volledig responsive en werkt op:
- Desktop computers
- Tablets
- Smartphones

## ✨ Features

- 🚀 **Ultra-modern design** met glassmorphism en neon accenten
- 🎨 **Indigo/Purple/Pink gradient thema** voor futuristic  look
- 💎 **Inter & Poppins lettertypen** - clean & professional
- ✨ Buttery smooth animaties en hover effecten
- 🌈 Gradient borders en glow effects
- 📱 Fully responsive (perfect op alle devices)
- 📋 Kopieerbaar server IP met moderne notification
- 🎯 Makkelijk aan te passen staff lijst en regels
- 🖼️ Logo integratie met blur en glow effecten
- 🎭 Backdrop blur en frosted glass effecten
- ⚡ Custom scrollbar met gradient styling
- 🌟 Animated background gradients

## 🎯 Design Inspiratie

Deze website is geïnspireerd door moderne Minecraft server websites met:
- Clean, minimalistisch design
- Glassmorphism UI trends
- Neon gradient accenten
- Professional gaming aesthetics
- Smooth, premium feel

## 🆘 Hulp Nodig?

Als je hulp nodig hebt met aanpassingen, neem dan contact op met een webontwikkelaar of vraag hulp op Discord/forums.

## 📝 Licentie

Dit template is gemaakt voor Remake Kingdom en kan vrij worden aangepast naar je wensen.
