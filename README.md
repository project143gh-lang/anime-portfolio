# Anime Portfolio

A beautiful anime-themed portfolio website built with Flask. Showcase your projects, skills, and personality with a stunning anime aesthetic.

## 📸 Screenshot

![Anime Portfolio Repository](./anime-portfolio.png)

**View the portfolio:** Open `http://localhost:5000` in your web browser after running the Flask app.

## Features

### 🎨 Design
- Anime-inspired visual theme with custom typography
- Color palette inspired by classic anime aesthetics
- Responsive layout that works on mobile and desktop
- Smooth animations and transitions

### 📄 Sections
- **Home**: Introduction with animated background
- **About**: Personal story and skills overview
- **Projects**: Showcase of your work with descriptions
- **Skills**: Technical skills with visual progress bars
- **Contact**: Contact form and social media links

### 📱 Responsiveness
- Mobile-first design approach
- Adapts to any screen size
- Touch-friendly interactions
- Optimized for all devices

### 🎯 Interactive Elements
- Hover animations on project cards
- Skill bar animations on scroll
- Smooth page transitions
- Cursor effects and micro-interactions

## 🚀 Quick Start

```bash
# 1. Install dependencies
pip install flask

# 2. Run the application
python app.py

# 3. Open in browser
# Visit: http://localhost:5000
```

## 🛠️ Project Structure

```
anime_portfolio/
├── app.py              # Flask application with all routes
├── server.log          # Server logs (auto-generated)
├── templates/          # HTML templates with anime theme
│   ├── base.html       # Base layout with common elements
│   ├── index.html      # Home page
│   ├── about.html      # About me page
│   ├── projects.html   # Projects showcase
│   ├── skills.html     # Skills progress bars
│   └── contact.html    # Contact form page
├── styles/             # CSS stylesheets
│   └── main.css        # Anime-themed styles
└── README.md           # This file
```

## 📁 Detailed Structure

```
templates/
├── base.html           # Contains navigation, footer, common styles
├── index.html          # Hero section with animated background
├── about.html          # Profile section with skills overview
├── projects.html       # Grid of project cards with hover effects
├── skills.html         # Circular progress bars for each skill
└── contact.html        # Form with validation and response

styles/main.css
├── Font imports (Google Fonts - anime aesthetic)
├── Reset and base styles
├── Navigation styling
├── Animation keyframes
├── Responsive media queries
├── Project card styles
├── Skill bar progress animations
└── Contact form styles
```

## 🎨 Customization

### Colors
Edit `styles/main.css` to modify:
- Primary anime color palette
- Background gradients
- Hover states

### Content
Modify `app.py` to:
- Change portfolio descriptions
- Update project links and images
- Add/remove skills
- Modify about text

### Images
Replace placeholder images in:
- Project card backgrounds
- Hero section backdrop
- Footer icons

## 📦 Dependencies

```bash
pip install flask
# No additional dependencies required!
```

## 📜 License

MIT

---

**K.bhalavardt, MIT Student**