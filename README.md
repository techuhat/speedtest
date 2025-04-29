# SimpleSpeed - Internet Speed Test

A lightweight, client-side internet speed test inspired by Fast.com that you can host on GitHub Pages.

![SimpleSpeed Demo](demo-screenshot.png)

## Features

- ⚡ Measures download speed
- 📤 Simulates upload speed
- 📶 Calculates ping
- 📱 Responsive design for all devices
- 🚀 No backend required - works entirely in the browser
- 🔄 Simple, clean UI with real-time speed updates

## Live Demo

Visit the live demo: [https://yourusername.github.io/simplespeed](https://yourusername.github.io/simplespeed)

## How to Use

1. Clone this repository
2. Customize the footer with your name and GitHub username
3. Enable GitHub Pages in your repository settings
4. Share your speed test with others!

## How It Works

SimpleSpeed uses JavaScript to:

1. **Download Test**: Downloads sample files from a CDN to measure download speed
2. **Upload Test**: Simulates an upload by generating data and processing it in chunks
3. **Ping Test**: Measures the round-trip time to a server

## Limitations

- The upload test is simulated since browsers have limited ability to measure true upload speeds without a dedicated server component
- Results may vary from other speed tests due to differences in methodology and test servers
- For most accurate results, run multiple tests and compare

## Customization

Feel free to customize the design by modifying the CSS variables at the top of the style section:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --background-color: #f8fafc;
    --text-color: #1e293b;
    --light-gray: #e2e8f0;
    --success-color: #10b981;
    --error-color: #ef4444;
}
```

## License

MIT License - feel free to use, modify, and distribute as you wish!

## Credits

Created by [Your Name]

---

If you like this project, give it a ⭐ on GitHub!
