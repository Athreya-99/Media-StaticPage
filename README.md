# 💕 Our Story - A Romantic Netflix-Style Website

A beautiful, fully-functional frontend website to share memories with your special someone. Built with HTML, CSS, and vanilla JavaScript - no backend required!

## 🎯 Features

✨ **Beautiful Design**
- Netflix-inspired profile selection screen
- Smooth animations and transitions
- Responsive design for all devices
- Modern gradient themes with pink and gold accents

🎬 **Video Support**
- Full video player for each profile
- Easy video switching
- Controls and playback options

📸 **Image Gallery**
- Responsive grid layout
- Hover effects with image titles
- Full-screen modal for viewing images
- Lazy loading support

🚀 **Production Ready**
- No dependencies needed
- Fast loading and smooth performance
- Mobile-friendly
- Easy to customize

## 📁 Project Structure

```
your-project/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript functionality
├── videos/             # Your video files
│   ├── memories.mp4
│   ├── moments.mp4
│   └── adventures.mp4
├── images/             # Your image files
│   ├── memory-1.jpg
│   ├── memory-2.jpg
│   └── ... (all other images)
└── README.md          # This file
```

## 🚀 Getting Started

### Step 1: Download the Files
You have 3 files:
- `index.html`
- `styles.css`
- `script.js`

### Step 2: Create Folders
Create two folders in the same directory as your HTML file:
- `videos/` - for video files
- `images/` - for image files

### Step 3: Add Your Media Files
Place your videos and images in their respective folders:
```
videos/
  ├── memories.mp4
  ├── moments.mp4
  └── adventures.mp4

images/
  ├── memory-1.jpg
  ├── memory-2.jpg
  ├── memory-3.jpg
  ├── memory-4.jpg
  ├── memory-5.jpg
  ├── memory-6.jpg
  ├── moment-1.jpg
  ├── moment-2.jpg
  ├── moment-3.jpg
  ├── moment-4.jpg
  ├── moment-5.jpg
  ├── moment-6.jpg
  ├── adventure-1.jpg
  ├── adventure-2.jpg
  ├── adventure-3.jpg
  ├── adventure-4.jpg
  ├── adventure-5.jpg
  └── adventure-6.jpg
```

### Step 4: Open in Browser
Double-click `index.html` to open in your browser!

## 🎨 Customization Guide

### Changing Profile Names and Emojis

Open `script.js` and find the `galleryData` object. Modify the profile information:

```javascript
memories: {
    name: 'Your Custom Name',      // Change the name
    emoji: '📸',                   // Change the emoji
    video: 'videos/memories.mp4',  // Your video path
    videoTitle: 'Your Title',      // Video title
    videoDescription: 'Your description...', // Video description
    items: [
        // Your images here
    ]
}
```

### Adding/Removing Images

In `script.js`, find the `items` array and add/remove image objects:

```javascript
items: [
    { id: 1, src: 'images/memory-1.jpg', title: 'Cute Name', date: 'When' },
    { id: 2, src: 'images/memory-2.jpg', title: 'Another Name', date: 'Date' },
    // Add more like this...
]
```

Each image needs:
- `id`: Unique number
- `src`: Path to your image file
- `title`: Sweet/cute name for the image
- `date`: When it was taken (e.g., "Day 1", "Week 2", "Today")

### Changing Colors

Open `styles.css` and find the `:root` section at the top:

```css
:root {
    --primary-color: #e50914;      /* Red - change this */
    --accent-pink: #ff69b4;        /* Pink - change this */
    --accent-gold: #ffd700;        /* Gold - change this */
    /* ... other colors */
}
```

**Popular Color Combinations:**
- Romantic: `#e50914`, `#ff69b4`, `#ffd700` (current)
- Purple Love: `#6f2da8`, `#c448d1`, `#e6b3ff`
- Ocean Blue: `#0066cc`, `#00ccff`, `#ffcc00`
- Sunset: `#ff6b35`, `#ff8c42`, `#ffd93d`

### Adding More Profiles

If you want more than 3 profiles:

1. **In `index.html`**, add a new profile card:
```html
<div class="profile-card" data-profile="newprofile">
    <div class="profile-image">🎨</div>
    <p class="profile-name">New Profile</p>
</div>
```

2. **In `script.js`**, add to `galleryData`:
```javascript
newprofile: {
    name: 'New Profile',
    emoji: '🎨',
    video: 'videos/newprofile.mp4',
    videoTitle: 'Title',
    videoDescription: 'Description',
    items: [
        // Your images...
    ]
}
```

### Adjusting Grid Layout

In `styles.css`, find the gallery grid and adjust:

```css
.gallery-grid {
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    /* Change 250px to make items bigger (300px) or smaller (200px) */
}
```

## 🎥 Video Format Guide

**Recommended Video Settings:**
- Format: `.mp4` (H.264 codec)
- Resolution: 1920x1080 (Full HD) or 1280x720 (HD)
- File Size: Under 100MB for fast loading
- Duration: 30 seconds to 5 minutes works best

**How to Convert Videos:**
Use free tools like:
- [HandBrake](https://handbrake.fr/) - Desktop app
- [CloudConvert](https://cloudconvert.com/) - Online tool
- [FFmpeg](https://ffmpeg.org/) - Command line (for technical users)

**Quick FFmpeg Command:**
```bash
ffmpeg -i input.mov -c:v libx264 -crf 23 -preset fast output.mp4
```

## 🖼️ Image Format Guide

**Recommended Image Settings:**
- Format: `.jpg` or `.png`
- Aspect Ratio: Square (1:1) works best for gallery
- Resolution: 1080x1080 px or higher
- File Size: Under 1MB each (use compression)

**Tools for Image Compression:**
- [TinyPNG](https://tinypng.com/) - Online, very easy
- [ImageOptim](https://imageoptim.com/) - Mac
- [FileOptimizer](https://nchc.org/fileoptimizer/) - Windows

## 🌐 Deploying to Vercel (Easy!)

### Step 1: Prepare Files
1. Make sure all your images and videos are in the correct folders
2. Test everything locally first by opening `index.html` in a browser

### Step 2: Create GitHub Repository
1. Go to [GitHub.com](https://github.com) and create a new repository
2. Clone it to your computer
3. Copy all files (index.html, styles.css, script.js, videos/, images/) into the folder
4. Push to GitHub

**Quick Git Commands:**
```bash
git add .
git commit -m "Add our story website"
git push origin main
```

### Step 3: Deploy to Vercel
1. Go to [Vercel.com](https://vercel.com)
2. Sign in with GitHub
3. Click "Import Project"
4. Select your repository
5. Click "Deploy"

**That's it!** Your website is now live!

### Alternative: Deploy to GitHub Pages
1. Push to GitHub (see Step 2)
2. Go to repository Settings → Pages
3. Select "Deploy from a branch"
4. Choose "main" branch
5. Save

Your site will be at: `https://yourusername.github.io/repository-name`

### Alternative: Deploy to Netlify
1. Go to [Netlify.com](https://netlify.com)
2. Click "Add new site" → "Deploy manually"
3. Drag and drop your project folder
4. Done! Get your live link immediately

## 🎯 Tips for the Best Gift

✨ **Make it Special:**
- Use cute nicknames for each image
- Add meaningful dates ("Our first date", "1 year together")
- Include videos of you singing, talking, or special moments
- Customize the profile names to something personal
- Change the colors to her favorite colors

📸 **Image Selection Tips:**
- Include a mix of close-ups and full body shots
- Add candid moments and posed photos
- Include nature/travel photos you took together
- Don't forget couple photos!
- Use bright, well-lit images for best display

🎬 **Video Ideas:**
- Compilation of favorite moments
- You talking about why you love her
- Highlights from trips together
- Montage set to your favorite song
- Message to her family and friends

## ❓ Troubleshooting

**Images not showing?**
- Check file paths match exactly (case-sensitive on some systems)
- Ensure image files are in the `images/` folder
- Try refreshing the page (Ctrl+Shift+R or Cmd+Shift+R)
- Check browser console for errors (F12)

**Videos not playing?**
- Ensure videos are in `.mp4` format
- Check video file is in the `videos/` folder
- Try a different browser (Chrome usually works best)
- Videos might be too large - compress to under 100MB

**Styling looks wrong?**
- Make sure `styles.css` is in the same folder as `index.html`
- Hard refresh your browser (Ctrl+Shift+R)
- Check file permissions

**Mobile looks weird?**
- The design is fully responsive - try refreshing
- Test in incognito/private mode
- Check that viewport meta tag is in HTML head

## 📱 Mobile Optimization

The website is fully optimized for:
- ✅ iPhones and iPads
- ✅ Android phones and tablets
- ✅ Desktop computers
- ✅ All modern browsers

Test on your phone by:
1. Uploading to Vercel/Netlify first, OR
2. Using browser developer tools (F12) → Toggle device toolbar

## 💡 Advanced Customization

### Change Font Styles
In `styles.css`, modify the font-family declarations:
```css
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
```

Suggestions: 'Georgia', 'Trebuchet MS', 'Arial', 'Courier New'

### Adjust Animation Speed
In `script.js` and `styles.css`, look for duration values:
```css
animation: fadeIn 0.6s ease-out;  /* 0.6s is the duration */
```
- Smaller number = faster (0.3s)
- Larger number = slower (1s)

### Add More Gallery Items
Just add more objects to the `items` array - the grid will automatically adjust!

## 🔒 Privacy & Security

This is a static website with NO backend:
- ✅ All data stays on the user's device
- ✅ No servers, no tracking
- ✅ No data collection
- ✅ Safe and secure for personal use

## 📞 Support Tips

If something breaks:
1. Check the browser console (F12 → Console tab)
2. Make sure file paths are correct
3. Try opening in a different browser
4. Delete browser cache and hard refresh
5. Check the README again for common issues

## 🎁 Delivery Tips

Perfect ways to share:
1. **Send the link**: Deploy and share the URL
2. **Download & Email**: Give her the folder with all files
3. **USB Drive**: Copy all files to USB stick
4. **Burn to Disc**: For a vintage touch (if her device supports it)
5. **Print QR Code**: Generate a QR code to the website and give it as a card

## 💝 Final Notes

This website is yours to customize endlessly:
- Change themes seasonally
- Add new memories regularly
- Update with new photos and videos
- Share with family and friends
- Make it your own!

Enjoy your gift! 🎉

---

**Made with 💕 for someone special**
