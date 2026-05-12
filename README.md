# 50 Years of Togetherness — Golden Jubilee Website

## ✦ How to Customize

### 1. Replace the couple's photo
In the `<div class="hero-photo-placeholder">` section, replace with:
```html
<img src="your-photo.jpg" alt="Couple photo" style="width:100%;height:100%;object-fit:cover">
```

### 2. Update names & dates
- Search for `Father & Mother` → replace with actual names
- Search for `1975` → replace with actual wedding year
- Search for `2025-11-15T18:00:00` → replace with actual celebration date

### 3. Update event details
Find the `#event` section and update:
- Date, time, venue name, address

### 4. Admin password
Default password: `family2025`
To change, find `if (pass === 'family2025')` and replace.

### 5. Add real photos to gallery
Replace the emoji placeholders with `<img>` tags or upload via the Admin panel.

### 6. Add YouTube videos
Paste any YouTube URL into the video section input box.

### 7. Customize family tree
Edit the SVG `<text>` elements with real family member names and birth years.

---

## 🚀 Deploy to Vercel (Free)

1. Create account at [vercel.com](https://vercel.com)
2. Create a new project → upload `index.html`
3. Done! You get a live URL like `golden-jubilee.vercel.app`

## 🌐 Deploy to GitHub Pages (Free)

1. Create a new GitHub repo
2. Upload `index.html` as the only file
3. Go to Settings → Pages → Branch: main → Save
4. Live at `https://yourusername.github.io/repo-name`

## 📱 Deploy to Netlify (Free)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the `index.html` file
3. Instant live URL!

---

## ✦ Features Included

- [x] Hero section with animated golden particles
- [x] Live countdown timer to celebration date
- [x] Interactive family journey timeline (7 milestones)
- [x] Photo gallery with 4 category filters + lightbox
- [x] Photo upload from device
- [x] Video memories section with YouTube embed support
- [x] Wishes & Blessings Wall (form + animated cards)
- [x] Interactive SVG Family Tree (3 generations)
- [x] Event details with RSVP button
- [x] Digital Memory Book (4-page flipbook)
- [x] Admin panel with password protection
- [x] WhatsApp sharing + link copy
- [x] Scroll reveal animations
- [x] Floating golden sparkles
- [x] Music toggle button (UI ready — add your audio src)
- [x] Fully responsive (mobile, tablet, desktop)
- [x] SEO meta tags

## 🎵 Adding Background Music

In the `<script>` section, find `toggleMusic()` and add:
```javascript
const audio = new Audio('your-song.mp3');
// Then in toggleMusic():
if (musicPlaying) { audio.play(); } else { audio.pause(); }
```

Suggested royalty-free music: [pixabay.com/music](https://pixabay.com/music)
Search for: "wedding", "classical piano", "romantic ambient"

---

Made with ♥ for a beautiful golden celebration.
