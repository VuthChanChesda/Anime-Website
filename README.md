# Top Anime Website 🎌

A modern, responsive anime ranking website featuring the best anime series and movies with ratings and reviews.

![Top Anime](https://img.shields.io/badge/Anime-Rankings-blue)
![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🌟 Features

- **Responsive Design** - Mobile-first, works on all devices
- **Dark Theme** - Modern dark UI with beautiful gradients
- **Real Anime Data** - Features top-rated anime with official posters
- **Star Ratings** - Visual rating system for each anime
- **Ad Integration** - Multiple ad slots ready for monetization
- **SEO Optimized** - Meta tags, Open Graph, and semantic HTML
- **Fast Loading** - Optimized images and minimal dependencies

## 🚀 Quick Start

### Deploy to Vercel (Recommended)

1. **Fork this repository** or download the files
2. **Connect to Vercel**:

   - Go to [vercel.com](https://vercel.com)
   - Sign up/Login with GitHub
   - Click "New Project"
   - Import your repository

3. **Configure deployment**:

   - Framework Preset: **Other**
   - Root Directory: `./`
   - Build Command: Leave empty (static site)
   - Output Directory: Leave empty

4. **Deploy**: Click "Deploy" and your site will be live!

### Local Development

```bash
# Clone the repository
git clone https://github.com/your-username/top-anime-website.git
cd top-anime-website

# Install Vercel CLI (optional)
npm install -g vercel

# Run local development server
vercel dev

# Or simply open index.html in your browser
open index.html
```

## 📁 Project Structure

```
top-anime-website/
├── index.html          # Main website file
├── vercel.json         # Vercel configuration
├── package.json        # Project metadata
├── .gitignore         # Git ignore rules
└── README.md          # This file
```

## 🎯 Ad Integration

The website includes multiple ad placement areas ready for your ad network:

- **Top Banner** (728x90) - Header area
- **In-feed Ad** - After 3rd anime card
- **Sidebar Ad** (300x600) - Desktop only
- **Bottom Banner** (728x90) - Before footer

### Adding Real Ads

Replace the placeholder ad slots with your actual ad code:

```html
<!-- Replace this -->
<div class="ad-slot">
  Top Banner Ad (728x90 placeholder)
  <small>Replace with Adsterra script</small>
</div>

<!-- With your ad network code -->
<div class="ad-slot">
  <!-- Your Adsterra/Google AdSense code here -->
</div>
```

## 🎨 Customization

### Adding New Anime

Edit the `animeList` array in `index.html`:

```javascript
const animeList = [
  {
    title: "Your Anime",
    description: "Brief description...",
    rating: 8.5,
    image: "https://your-image-url.jpg",
  },
  // ... more anime
];
```

### Styling

The website uses CSS custom properties for easy theming:

```css
:root {
  --bg: #0f1115; /* Background */
  --card: #161a22; /* Card background */
  --muted: #9aa4b2; /* Muted text */
  --text: #e9eef5; /* Main text */
  --accent: #4da3ff; /* Accent color */
  --ring: #223048; /* Border color */
}
```

## 📊 Performance

- **Lighthouse Score**: 95+ Performance
- **Mobile Friendly**: ✅ Responsive design
- **SEO Ready**: ✅ Meta tags and structured data
- **Fast Loading**: ✅ Optimized images and minimal CSS/JS

## 🔧 Technical Details

- **Framework**: Vanilla HTML/CSS/JavaScript
- **Hosting**: Vercel (static site)
- **Images**: External CDN links (Wikipedia, Amazon, etc.)
- **Responsive**: CSS Grid and Flexbox
- **Browser Support**: All modern browsers

## 📝 License

MIT License - feel free to use this for your own anime website!

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

Need help? Create an issue on GitHub or contact us.

---

**Made with ❤️ for anime fans worldwide** 🌍
