# ⚡ QUICK START GUIDE

## 5-Minute Setup

### 1️⃣ Download Files
You should have:
- ✅ index.html
- ✅ styles.css
- ✅ script.js
- ✅ README.md (full documentation)

### 2️⃣ Create Folders
Create 2 folders in the same location as your HTML file:
```
📁 videos/
📁 images/
```

### 3️⃣ Add Your Files

**Videos (at least one per profile):**
```
videos/
  ├── memories.mp4
  ├── moments.mp4
  └── adventures.mp4
```

**Images (6 per profile, 18 total):**
```
images/
  ├── memory-1.jpg through memory-6.jpg
  ├── moment-1.jpg through moment-6.jpg
  └── adventure-1.jpg through adventure-6.jpg
```

### 4️⃣ Test Locally
1. Double-click `index.html`
2. Wait for the loading animation
3. Click a profile
4. See your content!

---

## 🎨 Quick Customization

### Change Image Titles & Dates
Edit `script.js`, find the image name sections:

```javascript
{ id: 1, src: 'images/memory-1.jpg', title: 'Our First Kiss', date: 'Day 1' },
{ id: 2, src: 'images/memory-2.jpg', title: 'Coffee Talk', date: 'Week 1' },
```

### Change Profile Names
Edit `script.js`, find the profile definitions:

```javascript
memories: {
    name: 'Photos',      // ← Change this
    emoji: '📸',         // ← Or this
    ...
}
```

### Change Colors
Edit `styles.css`, find the colors at the very top:

```css
:root {
    --primary-color: #e50914;    /* Main red */
    --accent-pink: #ff69b4;      /* Heart pink */
    --accent-gold: #ffd700;      /* Sparkle gold */
}
```

---

## 🚀 Deploy in 3 Steps

### Option A: Vercel (Recommended)
1. Upload to GitHub
2. Go to vercel.com
3. Import from GitHub → Done!

### Option B: Netlify
1. Go to netlify.com
2. Drag & drop your folder
3. Get your link instantly!

### Option C: GitHub Pages
1. Push to GitHub
2. Settings → Pages
3. Enable with main branch

---

## ⚠️ Common Issues & Fixes

**Images not showing?**
- Make sure files are in `images/` folder
- Check spelling matches exactly in script.js
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)

**Videos not playing?**
- Must be `.mp4` format (H.264 codec)
- Check they're in `videos/` folder
- Try Chrome browser
- Might be too large - compress to under 100MB

**Page looks broken?**
- Refresh the page completely
- Make sure all 3 CSS/JS files are in the same folder
- Clear browser cache
- Try a different browser

---

## 📝 File Structure Checklist

Before uploading, verify you have:
```
✅ index.html (main file)
✅ styles.css (styling)
✅ script.js (logic)
✅ videos/ folder with your MP4 files
✅ images/ folder with your JPG/PNG files
```

All in the same root directory!

---

## 🎯 Image Naming Guide

Keep it simple. Use this format:

**Memories Profile:**
- memory-1.jpg = First memory
- memory-2.jpg = Second memory
- memory-3.jpg = Third memory
- ... etc

**Moments Profile:**
- moment-1.jpg through moment-6.jpg

**Adventures Profile:**
- adventure-1.jpg through adventure-6.jpg

Must match EXACTLY what you put in `script.js`!

---

## 💾 Backup Tips

Before uploading anywhere:
1. Keep a copy on your computer
2. Keep a copy on Google Drive
3. Keep a copy on USB drive

This way you never lose your memories!

---

## 🎁 Last Minute Tips

✨ **Make it romantic:**
- Use clear, well-lit photos
- Include some candid moments
- Add videos of YOU
- Customize the names to be cute & personal

📱 **Test on mobile:**
- Open the deployed link on her phone
- Make sure videos play smoothly
- Check all images load

🎨 **Double-check colors:**
- Make sure your chosen colors look good together
- Test on different lighting

---

## 📞 Need Help?

1. Check the full README.md file for detailed explanations
2. Check browser console (F12) for error messages
3. Make sure file paths in script.js match your actual files
4. Try opening in Chrome browser first

---

**You're all set! Enjoy your gift! 💕**
