# README.md

## 💖 Will You Be My Gurl! 💌

This project is a lovingly crafted interactive webpage that simulates a romantic confession experience. Built using HTML, CSS, and JavaScript, it walks the recipient through a playful and emotional proposal, enhanced by animations, cute bear gifs, custom dialogs, and a heartfelt message.

🔗 **Live Project**: [https://bemygurl.netlify.app/](https://bemygurl.netlify.app/)

---

## 📜 Overview

The webpage greets the user with a beautiful animated background and a clickable envelope. When clicked, a sequence of sweet messages and gifs play out using modal pop-ups (via SweetAlert2), ending in a proposal: **"Will you be my Gurl?"**. The recipient can respond with "Yes" or playfully try to click "No" (which becomes hard to click as a fun feature!).

---

## 💡 Features

- 💬 Sweet modals with animated stickers
- 🧸 Adorable animated bear gifs
- 🎨 Smooth background and blur transitions
- 🎶 Custom audio support (via `linkmp3` tag)
- 🧠 Typing animation for heartfelt messages
- ✨ Randomly floating hearts after "Yes" is clicked
- 📱 Fully responsive

---

## 🧰 Technologies Used

- HTML5 + CSS3
- JavaScript
- [SweetAlert2](https://sweetalert2.github.io/)
- Google Fonts (Ubuntu & Dancing Script)
- FontAwesome Icons

---

## 📁 File Structure

```plaintext
📦project-root
 ┣ 📂assets
 ┃ ┣ 📜cilukba.gif
 ┃ ┣ 📜g5.gif
 ┃ ┣ 📜gigitin.gif
 ┃ ┣ 📜lompatin.gif
 ┃ ┣ 📜tos.gif
 ┃ ┣ 📜wpjalanan.jpg
 ┃ ┗ 📜envelope.png
 ┗ 📜index.html
```

---

## ⚙️ How It Works

### HTML
- Uses structured `div` elements for layout.
- Envelope button triggers the sequence of events.
- `#Content` holds the interactive area.
- `audio` tag is dynamically filled but hidden by default.

### CSS
- Variables defined using `:root` for easy theming.
- Custom animations for scale, rotation, and heart float.
- Styling for popups, buttons, background blur, etc.
- Responsive behavior using flexbox and scaling.

### JavaScript
- Defines sequences using `async/await` with SweetAlert2 popups.
- Implements `memulai()`, `pesan()`, `jawab()`, `tolak()` etc. to drive the story.
- Hearts float from top to bottom when "Yes" is clicked.
- The "No" button moves on hover to playfully avoid rejection.
- Final WhatsApp redirection for message sending.

---

## 🎯 Deployment

This project is deployed using **Netlify** and can be accessed [here](https://bemygurl.netlify.app/).

---

## 🤝 Acknowledgements

- Cute gifs by various artists online.
- Inspired by sweet creative coding projects and romantic landing pages.

---

## 📌 License

This project is for personal and non-commercial romantic gestures only. ❤️

If you use or remix it, just give credit or tag **@gammaBytesofficial** 💫

---

## 🥰 Author

Built with love by Lucky Joshi ([@gammaBytesofficial](https://instagram.com/gammaBytesofficial))

