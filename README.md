# 🎬 Media Hub

A modern, beautifully designed personal media portal for accessing all your streaming services in one place.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)

## ✨ Features

- **Modern 2026 Design** - Glassmorphism, smooth animations, and gradient effects
- **Unified Portal** - Access all your media services from one elegant interface
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Keyboard Shortcuts** - Quick access using number keys (1-5)
- **Live Status** - Real-time connection status indicator
- **Zero Dependencies** - Pure HTML, CSS, and vanilla JavaScript

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)

1. Fork this repository
2. Go to **Settings** → **Pages**
3. Under **Source**, select **main** branch
4. Click **Save**
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Local Hosting

```bash
# Clone the repository
git clone https://github.com/yourusername/media-hub.git

# Open index.html in your browser
open index.html
```

## 📦 Services Included

| Service | Description | Icon |
|---------|-------------|------|
| **EMBY Server** | Main media streaming hub with transcoding support | 🎥 |
| **DhakaFlix** | Content index and streaming platform | 📚 |
| **DFlix Discovery** | Lightweight, mobile-optimized interface | ⚡ |
| **DhakaMovie** | Dedicated movie collection browser | 🎞️ |

## ⚙️ Configuration

All service URLs are pre-configured. If you need to modify them, edit the `serviceURLs` object in `index.html`:

```javascript
const serviceURLs = {
    'emby': 'http://media.ftpbd.net:8096/web/index.html#!/home',
    'dhakaflix-index': 'http://172.16.50.4/',
    'dhakaflix': 'http://172.16.50.4/',
    'dflix': 'https://dflix.discoveryftp.net/m',
    'dhakamovie': 'http://dhakamovie.com/netflix'
};
```

## ⌨️ Keyboard Shortcuts

- `1` - Launch EMBY Server
- `2` - Open DhakaFlix Index
- `3` - Start DhakaFlix Streaming
- `4` - Quick Access DFlix Discovery
- `5` - Explore DhakaMovie

## 🎨 Design Features

- **Glassmorphism Effects** - Frosted glass aesthetic with backdrop blur
- **Animated Backgrounds** - Dynamic gradient meshes with moving grid patterns
- **Micro-interactions** - Smooth hover effects and transitions
- **Color System** - Carefully crafted gradient palette
- **Typography** - System font stack for optimal performance
- **Accessibility** - Semantic HTML and proper contrast ratios

## 📱 Browser Support

- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera
- ⚠️ Internet Explorer (not supported)

## 🛠️ Customization

### Changing Colors

Edit the CSS variables in the `:root` section:

```css
:root {
    --primary: #6366f1;
    --secondary: #ec4899;
    --accent: #8b5cf6;
    /* ... */
}
```

### Adding New Services

1. Duplicate a service card in the HTML
2. Update the title, description, and icon
3. Add a new entry to `serviceURLs`
4. Update the `onclick` handler

### Modifying Stats

Edit the stats bar section to display your custom metrics:

```html
<div class="stat-card">
    <div class="stat-label">Your Label</div>
    <div class="stat-value">Your Value</div>
</div>
```

## 📸 Screenshots

The portal features:
- Clean, modern interface
- Smooth animations
- Responsive grid layout
- Professional glassmorphic cards
- Live status indicators

## 🔒 Privacy & Security

- **Local Only** - All code runs in your browser
- **No Tracking** - Zero analytics or external calls
- **No Data Collection** - Your information stays private
- **Open Source** - Fully transparent code

## 📄 License

This project is licensed under the MIT License - feel free to use it for personal projects.

## 🤝 Contributing

This is a personal project, but feel free to fork and customize for your own use!

## 💡 Tips

- Bookmark the page for quick access
- Add to home screen on mobile devices
- Use keyboard shortcuts for fastest navigation
- Works great with browser extensions

## 🔧 Troubleshooting

**Links not working?**
- Check that your services are accessible from your network
- Verify URLs in the `serviceURLs` configuration
- Ensure services are running and online

**Styling issues?**
- Clear browser cache
- Ensure you're using a modern browser
- Check for any browser extensions that might interfere

**Mobile display problems?**
- The site is fully responsive and should adapt automatically
- Try landscape mode for tablets

## 📞 Support

For issues or questions, open an issue in the repository.

---

**Made with ❤️ for personal media management**

*Last updated: February 2026*
