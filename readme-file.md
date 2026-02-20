# ☀️ Happy News India

> Spreading positivity, one story at a time

**Happy News India** is a positive news aggregator showcasing inspiring stories of everyday heroes, community champions, and change-makers across India. Built with React, this platform brings you daily doses of happiness and hope.

![Happy News India](https://img.shields.io/badge/version-1.0.0-orange?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)
![React](https://img.shields.io/badge/React-18.2-blue?style=for-the-badge&logo=react)

---

## ✨ Features

- 📰 **Real-time RSS Feed Aggregation** - Curated positive news from trusted sources
- 🎯 **Category Filtering** - Community Heroes, Nature, Culture, Sports, Education, Innovation
- ❤️ **Interactive Reactions** - Engage with stories through emoji reactions
- 📱 **Mobile Responsive** - Beautiful UI that works on all devices
- 🌐 **Multi-language Support** - English & Hindi (हिन्दी)
- 📊 **Admin Dashboard** - Content analytics and quality monitoring
- 🔄 **Pull-to-Refresh** - Seamless content updates
- 🚀 **Lightning Fast** - Built with Vite for optimal performance

---

## 🚀 Quick Start

### Prerequisites

- Node.js 16+ installed
- npm or yarn package manager

### Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/happy-news-india.git

# Navigate to project directory
cd happy-news-india

# Install dependencies
npm install

# Start development server
npm run dev
```

Visit `http://localhost:5173` in your browser 🎉

---

## 📦 Build for Production

```bash
# Create optimized production build
npm run build

# Preview production build locally
npm run preview
```

The built files will be in the `dist` folder, ready for deployment.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **React 18** | UI Framework |
| **Vite** | Build Tool & Dev Server |
| **Tailwind CSS** | Styling |
| **Lucide React** | Icons |
| **RSS Parser** | Feed Aggregation |

---

## 📁 Project Structure

```
happy-news-india/
├── src/
│   ├── components/       # React components
│   ├── assets/          # Images, fonts, etc.
│   ├── App.jsx          # Main application component
│   └── main.jsx         # Application entry point
├── public/              # Static assets
├── api/                 # Serverless functions (for deployment)
├── index.html           # HTML template
├── package.json         # Dependencies
├── vite.config.js       # Vite configuration
└── tailwind.config.js   # Tailwind configuration
```

---

## 🌍 Deployment

### Deploy to Vercel (Recommended)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/happy-news-india)

1. Push code to GitHub
2. Import project in Vercel
3. Deploy automatically!

### Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/YOUR_USERNAME/happy-news-india)

---

## 🎨 Customization

### Adding New RSS Feeds

Edit the `RSS_FEEDS` array in `src/App.jsx`:

```javascript
const RSS_FEEDS = [
  { 
    name: 'Your Source',
    url: 'https://example.com/feed/',
    category: 'Community Heroes',
    enabled: true
  },
  // Add more feeds...
];
```

### Changing Categories

Modify the `CATEGORIES` array in `src/App.jsx`:

```javascript
const CATEGORIES = [
  { id: 'custom-category', name: 'Custom', icon: YourIcon, gradient: 'from-color-to-color' },
  // Add more categories...
];
```

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- News sources: The Better India, Indian Express, NDTV
- Icons by [Lucide](https://lucide.dev)
- Built with ❤️ for spreading positivity

---

## 📧 Contact

- Website: [happynewsindia.com](https://happynewsindia.com)
- Email: contact@happynewsindia.com
- Twitter: [@HappyNewsIndia](https://twitter.com/happynewsindia)

---

## ⭐ Show Your Support

If this project brings a smile to your face, give it a ⭐️ on GitHub!

---

**Made with ☀️ in India**