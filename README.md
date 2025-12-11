# 🌌 CYBERPUNK GITHUB STATS DASHBOARD

<div align="center">

![GitHub Stats Dashboard](https://img.shields.io/badge/version-3.0-00f0ff?style=for-the-badge&logo=github)
![License](https://img.shields.io/badge/license-MIT-ff006e?style=for-the-badge)
![Stars](https://img.shields.io/badge/stars-⭐⭐⭐⭐⭐-ffff00?style=for-the-badge)
![Status](https://img.shields.io/badge/status-ACTIVE-39ff14?style=for-the-badge)

**The Most Beautiful & Professional GitHub Analytics Dashboard Ever Created**

[🌐 Live Demo](#live-demo) • [📸 Screenshots](#screenshots) • [🚀 Quick Start](#quick-start) • [✨ Features](#features) • [⚙️ Installation](#installation)

</div>

---

## ✨ HIGHLIGHTS

### 🎨 5 Premium Cyberpunk Themes
- **🌌 CYBER** - Classic cyan & pink vibes
- **✨ NEON** - Lime green & magenta energy
- **📟 MATRIX** - Green & yellow retro-futuristic
- **🌅 SYNTHWAVE** - Hot pink & cyan sunset
- **🌙 MIDNIGHT** - Blue & purple elegance

### 📊 Real-Time GitHub Analytics

✅ **Live Profile Data**
- Public repositories count
- Followers & Following statistics
- Public Gists counter
- Account age calculation
- Last updated timestamp

✅ **Advanced Features**
- Top 10 programming languages analysis
- Animated progress bars with glowing effects
- GitHub API token support (higher rate limits)
- User profile banner with avatar
- Bio, location, and company information
- Beautiful error handling

✅ **Professional Design**
- Fully responsive (desktop, tablet, mobile)
- Smooth animations & transitions
- Glitch effects & particle animations
- Scan line overlays
- Neon glow shadows
- Premium typography (Orbitron + Space Mono)
- Backdrop blur effects
- Zero dependencies (pure vanilla JS)

---

## 🎯 CORE FEATURES

### 🌟 Next-Generation UI/UX
- **Glitch Animations** - Retro-futuristic text effects
- **Neon Glow** - Dynamic shadow effects on hover
- **Particle System** - Floating background particles
- **Scan Lines** - CRT monitor aesthetic
- **Smooth Transitions** - Cubic-bezier animations
- **Hover Effects** - Interactive card elevations
- **Progress Animations** - Animated language bars

### 🎮 Interactive Controls
- **Real-Time Search** - Enter GitHub username to fetch stats
- **Theme Switcher** - 5 different visual themes
- **GitHub Token Input** - Optional for higher API limits
- **Keyboard Support** - Press Enter to fetch
- **Auto-Refresh** - Shows live timestamp

### 📈 Data Visualization
- **Stat Cards** - 6 beautiful metric displays
- **Language Bars** - Top 10 languages with percentages
- **Profile Banner** - User avatar and bio section
- **Status Messages** - Loading, success, error indicators
- **Real-Time Updates** - Live data synchronization

---

## 🚀 QUICK START

### Option 1: Use Directly (No Installation)
1. Visit: `https://github.com/AshrafMorningstar/github-stats-cyberpunk`
2. Click "Pages" in Settings
3. Enable GitHub Pages with `main` branch
4. Your dashboard is live!

### Option 2: Local Installation
```bash
# Clone the repository
git clone https://github.com/AshrafMorningstar/github-stats-cyberpunk.git
cd github-stats-cyberpunk

# Open in browser
open index.html
# or
start index.html
```

### Option 3: Deploy to GitHub Pages
```bash
git clone https://github.com/AshrafMorningstar/github-stats-cyberpunk.git
cd github-stats-cyberpunk
git push origin main
```
Then enable GitHub Pages in repository settings.

---

## 📸 FEATURES SHOWCASE

### Default Cyber Theme
✅ Cyan primary color with pink secondary
✅ Professional glitch effects
✅ Smooth animations throughout
✅ Beautiful stat cards
✅ Real-time language visualization

### Neon Theme
✅ Lime green primary color
✅ Magenta secondary accent
✅ High energy design
✅ Perfect for creative portfolios

### Matrix Theme
✅ Classic green on black
✅ Yellow accents
✅ Retro-futuristic feel
✅ Terminal aesthetic

### Synthwave Theme
✅ Hot pink primary
✅ Cyan secondary
✅ Yellow accents
✅ 80s sunset vibes

### Midnight Theme
✅ Blue primary color
✅ Purple secondary
✅ Light blue accents
✅ Elegant and professional

---

## ⚙️ INSTALLATION & SETUP

### Requirements
- Modern web browser (Chrome, Firefox, Safari, Edge)
- GitHub account
- Internet connection (for API calls)

### Steps

#### 1. **Local Setup**
```bash
git clone https://github.com/AshrafMorningstar/github-stats-cyberpunk.git
cd github-stats-cyberpunk
```

#### 2. **Open in Browser**
Simply double-click `index.html` or open with your favorite server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

#### 3. **Use Your GitHub Username**
- Enter your GitHub username (e.g., `AshrafMorningstar`)
- Optional: Add your GitHub token for higher API limits
- Click "FETCH STATS"

#### 4. **Switch Themes**
Click any theme button to instantly change the design!

---

## 🔑 GitHub API Token (Optional)

### Why Add a Token?
- **Higher Rate Limits**: 60 requests/hour → 5000 requests/hour
- **Private Repository Data**: (if applicable)
- **Better Reliability**: Avoid rate limiting

### How to Generate Token:
1. Go to [GitHub Settings → Developer Settings](https://github.com/settings/tokens)
2. Click "Generate new token (classic)"
3. Select scopes: `public_repo`, `read:user`
4. Copy the token
5. Paste in dashboard's "GitHub Token" field
6. **Important**: Never share your token publicly!

---

## 🎨 CUSTOMIZATION

### Change Colors
Edit the `:root` CSS variables in `<style>`:
```css
:root {
    --PRIMARY: #00f0ff;      /* Main cyan */
    --SECONDARY: #ff006e;    /* Secondary pink */
    --ACCENT: #9d00ff;       /* Accent purple */
}
```

### Add New Theme
1. Add to `themeConfigs` object in JavaScript:
```javascript
myTheme: {
    primary: '#your-color-1',
    secondary: '#your-color-2',
    accent: '#your-color-3'
}
```

2. Add button in HTML:
```html
<button class="theme-btn" data-theme="myTheme">🎨 MY THEME</button>
```

### Modify Languages Display
Edit the slice value in `fetchStats()`:
```javascript
.slice(0, 10)  // Change to show more/fewer languages
```

---

## 📱 RESPONSIVE DESIGN

### Breakpoints
- **Desktop**: 1024px+ (Full layout)
- **Tablet**: 768px - 1023px (2-column grid)
- **Mobile**: < 768px (1-column stack)
- **Small Mobile**: < 480px (Compact layout)

Works beautifully on all devices! 📱💻🖥️

---

## 🔐 Privacy & Security

✅ **100% Client-Side**
- No data stored on servers
- No cookies or tracking
- All processing happens in your browser
- GitHub API calls are direct (no intermediaries)

✅ **Token Safety**
- Token only sent to official GitHub API
- Never stored or logged
- Use in-browser storage only
- Can be revoked anytime in GitHub settings

---

## 🚀 DEPLOYMENT OPTIONS

### 1. **GitHub Pages** (Recommended)
- ✅ Free hosting
- ✅ Custom domain support
- ✅ SSL/HTTPS automatic
- ✅ One-click deployment

### 2. **Vercel**
```bash
npm install -g vercel
vercel
```

### 3. **Netlify**
- Drag & drop `index.html` to Netlify
- Custom domain available

### 4. **Your Own Server**
- Upload `index.html` to any web server
- No build process needed
- No dependencies required

---

## 📊 API ENDPOINTS USED

| Endpoint | Purpose | Rate Limit |
|----------|---------|------------|
| `/users/{username}` | User profile data | 60/hour |
| `/users/{username}/repos` | Repository list | 60/hour |
| `/users/{username}/repos?per_page=100` | Detailed repos | 60/hour |

With token: **5000 requests/hour** 🚀

---

## 🎯 KEYBOARD SHORTCUTS

| Key | Action |
|-----|--------|
| `Enter` | Fetch stats (in username field) |
| `Tab` | Navigate between inputs |
| `Click Theme` | Switch design theme |

---

## 🐛 TROUBLESHOOTING

### "User not found"
- ✅ Check GitHub username spelling
- ✅ Verify username is public
- ✅ Try without GitHub token first

### "Rate limit exceeded"
- ✅ Add a GitHub token (5000/hour limit)
- ✅ Wait 1 hour for reset
- ✅ Check API status

### Blank stats display
- ✅ Open browser console (F12)
- ✅ Check for errors
- ✅ Verify internet connection
- ✅ Clear browser cache

### Styling issues
- ✅ Hard refresh: `Ctrl+Shift+R` (Windows) or `Cmd+Shift+R` (Mac)
- ✅ Clear browser cache
- ✅ Try different browser

---

## 🔄 GITHUB ACTIONS AUTOMATION

### Automated Weekly Stats Generation
Create `.github/workflows/stats.yml`:
```yaml
name: Generate Stats

on:
  schedule:
    - cron: '0 0 * * 0'  # Weekly on Sunday
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Generate stats
        run: node scripts/generate-stats.js
```

---

## 📦 PROJECT STRUCTURE

```
github-stats-cyberpunk/
├── index.html              # Main dashboard (all-in-one)
├── README.md               # This file
├── LICENSE                 # MIT License
├── .github/
│   └── workflows/
│       └── stats.yml       # GitHub Actions automation
└── assets/                 # Screenshots & images
```

---

## 📚 LEARNING RESOURCES

- **GitHub API Docs**: https://docs.github.com/en/rest
- **CSS Animations**: https://developer.mozilla.org/en-US/docs/Web/CSS/animation
- **JavaScript Fetch**: https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
- **Web Design**: https://dribbble.com

---

## 💡 TIPS & TRICKS

### 🌟 Pro Tips
1. **Bookmark your dashboard** - Quick access to your stats
2. **Share the link** - Show off your GitHub profile in style
3. **Use different tokens** - One for personal, one for org projects
4. **Export as bookmark** - Add to GitHub README

### 🎨 Design Inspiration
- Look at theme transitions
- Hover over stat cards
- Watch language bars animate
- Notice the glitch effect on title

---

## 🤝 CONTRIBUTING

Want to improve this project? 
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

## 📄 LICENSE

This project is licensed under the **MIT License** - see [LICENSE](LICENSE) file for details.

```
MIT License © 2024 Ashraf Morningstar
Permission is hereby granted, free of charge, to any person obtaining a copy...
```

---

## 👨‍💻 ABOUT CREATOR

**Ashraf Morningstar**
- 🌐 GitHub: [@AshrafMorningstar](https://github.com/AshrafMorningstar)
- 🐦 Twitter: [@AMS_Morningstar](https://twitter.com/AMS_Morningstar)
- 📍 Location: India
- 💼 Company: MorningStar Construction

---

## 🌟 SHOW YOUR SUPPORT

- ⭐ **Star this repository** - Show your love
- 🔗 **Share the link** - Tell your friends
- 💬 **Leave feedback** - Suggestions & ideas welcome
- 🐛 **Report issues** - Help improve the project
- 🍴 **Fork it** - Create your own version

---

## 📞 CONTACT & SUPPORT

- 📧 Email: ashrafmorningstar@gmail.com
- 💬 GitHub Issues: Report bugs here
- 🐦 Twitter: @AMS_Morningstar
- 📱 WhatsApp: Available on GitHub profile

---

## 🎯 ROADMAP

### v3.0 (Current)
- ✅ 5 premium themes
- ✅ Real-time GitHub stats
- ✅ Responsive design
- ✅ Beautiful animations

### v4.0 (Planned)
- 🔄 More themes (10+)
- 📊 Advanced analytics
- 📈 Contribution graphs
- 🎬 Animated GIF generation
- 🔔 Notification system

### v5.0 (Future)
- 🌍 Multi-language support
- 🔐 OAuth authentication
- ☁️ Cloud storage
- 📱 Mobile app

---

<div align="center">

### 🚀 START YOUR JOURNEY NOW!

[⭐ Star on GitHub](https://github.com/AshrafMorningstar/github-stats-cyberpunk) • [🌐 View Dashboard](#) • [📧 Contact Me](mailto:ashrafmorningstar@gmail.com)

**Made with ❤️ by Ashraf Morningstar**

</div>

---

*Last updated: December 11, 2024 | v3.0 | All systems online ✅*