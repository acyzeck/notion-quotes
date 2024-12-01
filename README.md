# Notion Embedded Quotes

A collection of minimalist, elegant quote generators built specifically for embedding in Notion pages. Features different collections of wisdom including Japanese concepts, Atomic Habits principles, and Marcus Aurelius meditations.

![Demo](assets/demo.gif)

## 🔗 Live Demos

- Japanese Wisdom: `https://danhilse.github.io/notion-quotes/kototama/`
- Atomic Habits: `https://danhilse.github.io/notion-quotes/atomic/`
- Marcus Aurelius: `https://danhilse.github.io/notion-quotes/stoic/`

## 🎯 Features

- Clean, modern design with proper typography
- Smooth animations and transitions
- Randomized quotes on page load
- Click-to-shuffle functionality
- Fully responsive and embedded-friendly
- Different styles for different content types:
  - Japanese quotes with phonetic readings
  - Atomic Habits with implementation tips
  - Meditations with reflections and context

## 📝 Usage in Notion

1. Choose your desired quote collection:
```
/kototama/ - Japanese wisdom and concepts
/atomic/   - Atomic Habits principles and tips
/stoic/    - Marcus Aurelius meditations
```

2. Create an embed block in your Notion page

3. Paste the URL with a version parameter to prevent caching:
```
https://danhilse.github.io/notion-quotes/kototama/?v=1
https://danhilse.github.io/notion-quotes/atomic/?v=1
https://danhilse.github.io/notion-quotes/stoic/?v=1
```

### Important: Updating and Cache Busting

Notion caches embedded content. To see updates after making changes:

1. Increment the version number in your embed URL:
```
https://danhilse.github.io/notion-quotes/kototama/?v=1  // Initial
https://danhilse.github.io/notion-quotes/kototama/?v=2  // After updates
```

2. Replace the old embed with a new one using the updated URL

Alternatively, you can use a timestamp:
```
https://danhilse.github.io/notion-quotes/kototama/?t=20231130
```

## ✨ Customization

### Quote Collections

#### Japanese Wisdom (kototama)
```javascript
const quotes = [
    {
        japanese: "改善",
        phonetic: "Kaizen",
        translation: "Change for the better - continuous improvement in small steps"
    }
];
```

#### Atomic Habits (atomic)
```javascript
const cards = [
    {
        main: "Use habit stacking to build new habits",
        implementation: "After [CURRENT HABIT], I will [NEW HABIT]",
        source: "Implementation Strategy - Atomic Habits"
    }
];
```

#### Marcus Aurelius (stoic)
```javascript
const meditations = [
    {
        quote: "The best revenge is not to be like your enemy.",
        book: "Book VII",
        reflection: "Focus on your own virtue rather than others' vices."
    }
];
```

### Styling
Each collection has its own styled container in its respective HTML file. The designs use:
- Clean typography with Inter font family
- Minimal color palette
- Fade-in animations
- Responsive layouts

## 📂 Project Structure
```
notion-quotes/
├── index.html          # Landing page/directory
├── kototama/          
│   └── index.html      # Japanese wisdom quotes
├── atomic/
│   └── index.html      # Atomic Habits cards
├── stoic/
│   └── index.html      # Marcus Aurelius meditations
└── assets/
    └── demo.gif        # Demo animation
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

## 📄 License

MIT License - see LICENSE file for details