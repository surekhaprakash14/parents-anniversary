# 🎉 Anniversary Webpage Customization Guide

## How to Customize Your Anniversary Tribute

### 1. **Add Your Photos** 📸

To replace the placeholder photos with your actual family photos:

**Option A: Using Online Image URLs**
1. Open `index.html` in a text editor
2. Find the slideshow section (look for `<div class="slide">`)
3. Replace each `<div class="slide-placeholder">` with:
```html
<img src="YOUR_IMAGE_URL_HERE" alt="Memory">
```

**Option B: Upload Images to Your Repository**
1. Add your image files to the repository (Photos folder)
2. Replace placeholder with:
```html
<img src="photos/your-photo-name.jpg" alt="Memory">
```

### 2. **Edit the Message** 💌

Find the message section and customize:
```html
<div class="message">
    <p>Happy Anniversary, Mom & Dad!</p>
    <br>
    <p>Your custom message here...</p>
    <div class="signature">
        With all my love,<br>
        Your Name ❤️
    </div>
</div>
```

### 3. **Change the Background Music** 🎵

Replace the music URL in the audio player:
```html
<audio controls>
    <source src="YOUR_MUSIC_URL_HERE" type="audio/mpeg">
</audio>
```

Suggested royalty-free music sources:
- Pixabay Music: https://pixabay.com/music/
- Bensound: https://www.bensound.com/
- Free Music Archive: https://freemusicarchive.org/

### 4. **Update Slide Captions**

Find and modify:
```html
<div class="slide-text">Your caption here</div>
```

### 5. **Enable GitHub Pages** 🌐

To make it live:
1. Go to your repository: https://github.com/surekhaprakash14/parents-anniversary
2. Click **Settings** → **Pages**
3. Under "Source", select **Main** branch
4. Your site will be live at: `https://surekhaprakash14.github.io/parents-anniversary/`

### 6. **Share the Link** 📤

Share the GitHub Pages link with your parents! They can view it on any device.

### 7. **Colors & Styling** (Advanced)

To change colors, find the `<style>` section and modify:
- Main color: `#e63946` (red/pink)
- Background gradient: `linear-gradient(135deg, #667eea 0%, #764ba2 100%)`
- Message background: `rgba(230, 57, 70, 0.1)`

## Features Included

✨ **Automatic Effects:**
- Floating hearts (continuously)
- Falling rose petals
- Sparkle effects on "Celebrate Now!" button
- Heartbeat animation on title
- Smooth slideshow transitions

🎯 **Interactive Elements:**
- Photo slideshow with Previous/Next buttons
- Dot indicators for slides
- Keyboard navigation (arrow keys)
- Celebration button for special effects
- Background music player

📱 **Responsive Design:**
- Works on desktop, tablet, and mobile
- Touch-friendly buttons
- Adaptive font sizes

## Tips for Best Results

1. Use high-quality photos for best appearance
2. Compress large images before uploading
3. Test on mobile devices before sharing
4. Play background music quietly
5. Share the link via email, WhatsApp, or social media

---

Enjoy creating this beautiful anniversary tribute! 💕
