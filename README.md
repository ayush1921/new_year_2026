# New Year 2026 Countdown & Wishes 🎊✨

A complete, interactive New Year countdown webpage with festive animations, fireworks, and customizable wishes!

## Features

### 🕒 Live Countdown Timer
- Real-time countdown to **January 1, 2026 00:00:00 IST**
- Large, glowing digits showing Days, Hours, Minutes, and Seconds
- Pulsing animations with golden gradient effects

### 🎆 Fireworks & Visual Effects
- **Animated stars background** - Twinkling stars using HTML5 Canvas
- **Continuous fireworks** - Beautiful fireworks that launch randomly
- **Sound effects** - Fireworks sound plays when each firework bursts!
- **Floating moon** - Animated moon with glow effects
- **Dark cosmic theme** - Gradient background with gold accents

### 🎉 Confetti System
- **Massive burst at midnight** - 200+ particle confetti explosion
- **Click anywhere** - Trigger confetti and fireworks at any location
- Smooth, optimized performance using canvas-confetti library

### 🎵 Audio Effects
- Fireworks sound plays **the moment each firework bursts**
- Auto-plays on New Year (with browser policy fallback)
- Plays on user clicks and interactions
- Volume-optimized for pleasant experience

### 🎨 **NEW: Customizable Wishes**

#### How to Customize:
1. Click the **"Customize & Share"** button
2. Fill in:
   - **From**: Your name
   - **To**: Recipient's name
   - **Custom Message**: Your personalized New Year message
3. Click **"Preview"** to see how it looks
4. Click **"Generate Link"** to create a unique shareable URL

#### How It Works:
- Each customization generates a **unique encoded URL** like:
  ```
  https://yoursite.com/index.html?code=eyJmcm9tIjoiSm9obiIsInRv...
  ```
- The code contains all your custom data (name, recipient, message, timestamp)
- Anyone who opens your link will see **your personalized message**!

#### Example Custom Link:
```
index.html?code=eyJmcm9tIjoiU2FyYWgiLCJ0byI6IkFsZXgiLCJtZXNzYWdlIjoiV2lzaGluZyB5b3UgYW4gYW1hemluZyAyMDI2IGZpbGxlZCB3aXRoIGFkdmVudHVyZXMgYW5kIHN1Y2Nlc3MhIiwidGltZXN0YW1wIjoxNzA0MDY3MjAwMDAwfQ==
```

### 📱 Responsive Design
- Mobile and desktop optimized
- Touch-friendly interactions
- Scales beautifully from 320px to 4K screens

### 🔗 Easy Sharing
- **Quick Share** - Share the current page instantly
- **Customize & Share** - Create personalized wishes with unique links
- Web Share API with clipboard fallback
- Includes your custom message in shared text

## Usage

### Basic Usage:
Simply open `index.html` in any modern browser - no server required!

### Creating Custom Wishes:
1. Open the page
2. Click "Customize & Share"
3. Enter your details
4. Generate and copy the link
5. Share with friends and family!

### URL Parameters:
The page supports URL parameters for custom wishes:
- `?code=ENCODED_DATA` - Displays custom wishes

The code is a Base64-encoded JSON object containing:
```javascript
{
  "from": "Your Name",
  "to": "Recipient Name",
  "message": "Your custom message",
  "timestamp": 1704067200000
}
```

## Browser Compatibility
- Chrome/Edge: Full support ✅
- Firefox: Full support ✅
- Safari: Full support ✅
- Mobile browsers: Full support ✅

## Audio Note
Due to browser autoplay policies:
- Audio will attempt to play automatically at midnight
- Click anywhere to enable sound if it doesn't auto-play
- Fireworks burst sounds play after first user interaction

## Dependencies
- [canvas-confetti](https://www.npmjs.com/package/canvas-confetti) - CDN loaded
- Fireworks audio from [Mixkit](https://mixkit.co/free-sound-effects/fireworks/)

## Files
- `index.html` - Complete standalone webpage (all CSS/JS embedded)
- `README.md` - This file

## Tips for Best Experience
1. Open a few minutes before midnight on New Year's Eve
2. Click anywhere to enable audio before midnight
3. Share custom links with unique messages for each friend
4. Use fullscreen mode for maximum impact
5. Turn up your volume for the fireworks sounds! 🔊

## Customization Examples

### For a Friend:
- **From**: "Sarah"
- **To**: "Alex"
- **Message**: "Wishing you an incredible 2026 filled with adventures, laughter, and all the success you deserve! Let's make amazing memories together!"

### For Family:
- **From**: "The Johnson Family"
- **To**: "Grandma & Grandpa"
- **Message**: "Happy New Year! May 2026 bring you health, happiness, and lots of precious moments with loved ones. We love you!"

### For Colleagues:
- **From**: "Tech Team"
- **To**: "Everyone"
- **Message**: "Here's to crushing our goals in 2026! May this year bring innovation, growth, and success to all of us. Happy New Year!"

## License
Free to use and customize for personal and commercial projects.

---

**Made with ❤️ for celebrating New Year 2026!**

🎆 May your year be filled with joy, success, and endless possibilities! 🎆
