# Japanese Photography Quotes Generator

A minimalist, elegant quote generator featuring Japanese photography and creativity-related expressions. Built specifically for embedding in Notion pages.

![Demo](assets/demo.png)

## 🔗 Live Demo
https://danhilse.github.io/notion-quotes/

## 🎯 Features
- Clean, modern design with proper Japanese typography
- Smooth animations and transitions
- Click-to-shuffle functionality
- 15 curated Japanese expressions related to photography and creativity
- Fully responsive and embedded-friendly

## 📝 Usage in Notion

1. Visit the live URL: `https://danhilse.github.io/notion-quotes/`
2. Create an embed block in your Notion page
3. Paste the URL with a version parameter to prevent caching:
```
https://danhilse.github.io/notion-quotes/?v=1
```

### Important: Updating and Cache Busting

Notion caches embedded content. To see updates after making changes:

1. Increment the version number in your embed URL:
```
https://danhilse.github.io/notion-quotes/?v=1  // Initial
https://danhilse.github.io/notion-quotes/?v=2  // After updates
https://danhilse.github.io/notion-quotes/?v=3  // And so on
```

2. Replace the old embed with a new one using the updated URL

Alternatively, you can use a timestamp:
```
https://danhilse.github.io/notion-quotes/?t=20231130
```

## 🛠️ Setup for Development

1. Clone the repository:
```bash
git clone https://github.com/danhilse/notion-quotes.git
cd notion-quotes
```

2. Deploy to GitHub Pages:
   - Go to repository Settings
   - Navigate to Pages section
   - Set source to `main` branch
   - Save

3. Your quote generator will be available at `https://danhilse.github.io/notion-quotes/`

## ✨ Customization

### Adding New Quotes
Edit the `quotes` array in `index.html`:

```javascript
const quotes = [
    {
        japanese: "改善",
        phonetic: "Kaizen",
        translation: "Change for the better - continuous improvement in small steps"
    },
    // Add new quotes here
];
```

### Styling
All styles are contained in the `<style>` section of `index.html`. The design uses:
- Noto Serif JP for Japanese characters
- Noto Sans JP for phonetic and translations
- Minimal color palette
- Fade-in animations

## 📄 License
MIT

## 🤝 Contributing
Feel free to submit issues and enhancement requests!
