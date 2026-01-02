# Sanket Mehta - Portfolio Website

Interactive portfolio showcasing 7+ years of data engineering experience, specializing in Databricks and Unity Catalog.

## 🚀 Quick Deploy to GitHub Pages

### Option 1: Simple HTML Deployment (Recommended - Fastest)

This is the **easiest** way to get your portfolio live on GitHub Pages.

1. **Create a new GitHub repository**
   ```bash
   # On GitHub.com, create a new repo named: yourusername.github.io
   # Replace 'yourusername' with your actual GitHub username
   # Example: sanketmehta7.github.io
   ```

2. **Clone and add files**
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   cd yourusername.github.io
   
   # Copy index.html to this directory
   # Or create index.html and paste the content
   ```

3. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial portfolio commit"
   git push origin main
   ```

4. **That's it!** 🎉
   - Your site will be live at: `https://yourusername.github.io`
   - It usually takes 1-2 minutes to deploy
   - No build process needed!

---

### Option 2: Using a Custom Repository Name

If you want to use a different repo name (e.g., `portfolio`):

1. **Create repository** (any name, e.g., `portfolio`)

2. **Enable GitHub Pages**
   - Go to repo Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` / `root`
   - Click Save

3. **Your site will be at:** `https://yourusername.github.io/portfolio`

---

## 🎨 Customization Guide

### Change Colors
Find and replace gradient colors in the HTML:

```html
<!-- Main gradients -->
from-blue-400 to-purple-400    → Change to your preferred colors
from-slate-900 via-slate-800   → Background colors

<!-- Common color replacements -->
blue-400  → cyan-400, emerald-400, indigo-400
purple-400 → violet-400, fuchsia-400
pink-400   → rose-400, red-400
```

### Update Content

Edit these sections in `index.html`:

**Personal Info** (around line 25):
```javascript
const titles = [
    'Your Title 1',
    'Your Title 2',
    // Add more titles
];
```

**Skills** (around line 50):
```javascript
const skills = {
    technical: [
        { name: 'Python', level: 95, category: 'engineering' },
        // Add/modify skills
    ]
}
```

**Experience** (around line 80):
```javascript
const experience = [
    {
        company: 'Company Name',
        role: 'Your Role',
        // Modify details
    }
]
```

### Add Google Analytics

Add before `</head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

---

## 📱 Features

- ✨ Animated typing effect for role titles
- 📊 Interactive skill progress bars
- 🎯 Filterable experience timeline (All / Leadership / Technical / Foundation)
- 📖 Expandable role details
- 🏆 Certification badges
- 📱 Fully responsive design
- 🎨 Modern gradient design
- ⚡ Single-file deployment (no build needed!)

---

## 🛠️ Tech Stack

- React 18 (via CDN)
- TailwindCSS (via CDN)
- Vanilla JavaScript
- No build process required!

---

## 🔧 Troubleshooting

**Site not showing up?**
- Wait 2-3 minutes after first push
- Check Settings → Pages is enabled
- Ensure file is named `index.html`
- Clear browser cache (Ctrl+Shift+R)

**Want to test locally?**
```bash
# Option 1: Python
python -m http.server 8000

# Option 2: Node.js
npx serve

# Then open: http://localhost:8000
```

**Need HTTPS?**
- GitHub Pages automatically provides HTTPS
- Custom domain: Settings → Pages → Custom domain

---

## 📝 Custom Domain Setup (Optional)

1. **Buy domain** (from Namecheap, GoDaddy, etc.)

2. **Add DNS records:**
   ```
   Type: A
   Name: @
   Value: 185.199.108.153
   Value: 185.199.109.153
   Value: 185.199.110.153
   Value: 185.199.111.153
   
   Type: CNAME
   Name: www
   Value: yourusername.github.io
   ```

3. **In GitHub repo:**
   - Settings → Pages → Custom domain
   - Enter: `yourdomain.com`
   - Check "Enforce HTTPS"

---

## 🚀 Want a Full React App Instead?

Let me know if you want:
- Proper React project structure
- Vite/Create React App setup
- Build optimization
- Better development experience
- Component separation

I can create that too! This HTML version is great for simplicity, but a proper React setup gives you more flexibility for future updates.

---

## 📄 License

Feel free to fork and customize for your own use!

---

## 🤝 Connect

- LinkedIn: [linkedin.com/in/sanketmehta7](https://linkedin.com/in/sanketmehta7)
- Blog: [tinyurl.com/sanketsblog](https://tinyurl.com/sanketsblog)
- Email: sanketmehta765@gmail.com

---

**Need help?** Open an issue or reach out directly!