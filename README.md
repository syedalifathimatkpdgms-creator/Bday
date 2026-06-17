# 🎂 Birthday Surprise Website

A beautiful, interactive birthday surprise website for your best friend!

## Features ✨

- 🔐 **Password Protected** - Secure entry with password authentication
- 💜 **Personalized Message** - Heartfelt birthday wishes
- 🎵 **Music Player** - Add your favorite songs
- 🎂 **Birthday Celebration** - Animated birthday wish
- 📸 **Photo Gallery** - Display cherished memories
- 📱 **Responsive Design** - Works on all devices
- ✨ **Smooth Animations** - Beautiful transitions and effects

## Setup Instructions 📋

### 1. Add Media Files

Create an `assets` folder and add your files:

```
assets/
├── song.mp3          (Your favorite song)
├── pic1.jpg          (Memory photo 1)
├── pic2.jpg          (Memory photo 2)
└── pic3.jpg          (Memory photo 3)
```

### 2. Customize

Edit `index.html` to:
- Change the password (default: "friend")
- Update the birthday message
- Add your photos and song

### 3. Deploy

#### Option A: GitHub Pages (Free)
1. Go to Settings → Pages
2. Select `main` branch as source
3. Your site will be live at `https://yourusername.github.io/Bday`

#### Option B: Netlify (Free)
1. Connect your GitHub repo to Netlify
2. Deploy with one click

#### Option C: Local
Just open `index.html` in your browser

## Customization 🎨

### Change Password
Find this line in the script:
```javascript
if(pass==="friend"){
```
Replace `"friend"` with your desired password

### Modify Messages
Edit the text in each `<p>` tag to personalize the message

### Update Colors
Change `#8b5cf6` to your favorite color throughout the CSS

## Default Password 🔑
**Password:** `friend`

## File Structure 📁
```
Bday/
├── index.html        (Main website)
├── README.md         (This file)
├── assets/
│   ├── song.mp3
│   ├── pic1.jpg
│   ├── pic2.jpg
│   └── pic3.jpg
└── .gitignore
```

## Browser Support 🌐
- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Mobile browsers ✅

## Tips 💡

1. **Best image size:** 500x400px or similar aspect ratio
2. **Audio format:** MP3 works best for compatibility
3. **Mobile friendly:** Already optimized for phones
4. **Password hint:** Keep it something meaningful to your friend

## License 📄
Feel free to use and modify for personal use!

---

**Made with ❤️ for your bestfriend's special day!**
