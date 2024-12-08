# Notion Embedded Quotes

A collection of minimalist, elegant quote generators built specifically for embedding in Notion pages. Features different collections of wisdom including Japanese concepts, Atomic Habits principles, Marcus Aurelius meditations, and more.

![Demo](assets/demo.gif)

## Live Demos

- Japanese Wisdom: `https://danhilse.github.io/notion-quotes/kototama/`
- Atomic Habits: `https://danhilse.github.io/notion-quotes/atomic-habits/`
- Marcus Aurelius: `https://danhilse.github.io/notion-quotes/stoic/`
- Tao Te Ching: `https://danhilse.github.io/notion-quotes/tao/`
- First Principles: `https://danhilse.github.io/notion-quotes/first/`
- Zen Koans: `https://danhilse.github.io/notion-quotes/koan/`
- Cognitive Biases: `https://danhilse.github.io/notion-quotes/bias/`

## Features

- Clean, modern design with proper typography
- Smooth animations and transitions
- Randomized quotes on page load
- Click-to-shuffle functionality
- Fully responsive and embedded-friendly
- One-click copy for Notion embedding
- Different styles for different content types:
  - Japanese quotes with phonetic readings
  - Atomic Habits with implementation tips
  - Meditations with reflections and context
  - Tao Te Ching with original Chinese and pinyin
  - First Principles with examples and exercises
  - Zen Koans with commentaries
  - Cognitive Biases with recognition patterns

## Usage in Notion

1. Visit our [homepage](https://danhilse.github.io/notion-quotes/) and click on any quote collection to copy its embed URL
2. Create an embed block in your Notion page
3. Paste the copied URL

Or manually choose from these collections:
```
/kototama/      - Japanese wisdom and concepts
/atomic-habits/  - Atomic Habits principles and tips
/stoic/         - Marcus Aurelius meditations
/tao/           - Tao Te Ching wisdom with Chinese text
/first/         - First Principles thinking methods
/koan/          - Zen Koans and commentaries
/bias/          - Common Cognitive Biases
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

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

## License

MIT License - see LICENSE file for details