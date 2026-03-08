# Anniversary Website — A Gift for Friends

This interactive website was created to celebrate a friend's first anniversary. It features a timeline of months, a countdown since the start date, a fun "VS" game to determine who is the best person, background music, confetti animations, and special effects for month 14.

I helped a friend put this together – it's fully customisable and ready to be filled with your own memories.

## ✨ Features

- **Splash screen** with floating hearts and entrance options.
- **Countdown timer** showing days/hours/minutes/seconds since the relationship began (default: Dec 30, 2024).
- **Interactive timeline** – tap any month card to view a photo, description, and date ribbon. Includes months up to 14 (with a special animated Month 14).
- **VS Game** – a level‑based game where you pick who wins each round. The goal: always choose "Her" to win. Wrong picks unlock new opponents. At level 6, a plot twist declares her the winner.
- **Background music** – toggle play/pause and mute/unmute via top controls.
- **Confetti & heart bursts** – triggered when you celebrate (e.g., final button in Month 14 or game victory).
- **Month 14 special** – golden autumn theme with animated branches, a sunflower that plays a video when clicked, falling leaves, and a smooth colour transition.
- **Year reveal animation** – when moving from Month 12 to Month 13, a dramatic 2025 → 2026 transition plays.
- **Fully responsive** – works on mobile and desktop. Touch swipe to navigate months.
- **Share button** – copy link or use native share.

## 🚀 Getting Started

1. **Download/clone** this repository.
2. **Add your media** – place your images, audio, and video in the appropriate `public/` subfolders, matching the names used in the HTML (or update the `src` attributes).
3. **Open `index.html`** in any modern browser. No build step required – it’s pure HTML, CSS, and JavaScript.

For the best experience, use a mobile device or enable mobile view in your browser’s developer tools.

## 🎮 How to Use

- **Begin Our Journey** – enters the main timeline.
- **Preview Timeline** – jumps directly to the first month.
- **Month cards** – tap any month to see its photo and description.
- **Navigation buttons** – inside each month, use Back/Next to browse, or swipe left/right on touch devices.
- **Home button** (house icon) – returns to the main timeline.
- **Music controls** – play/pause (▶/❚❚) and mute/unmute (speaker icon).
- **Share button** – shares the page link.
- **VS Game** – found on the timeline grid. Choose between two cards – only picking "Her" is correct. The game resets when you leave and re-enter the section.
- **Month 14** – watch the golden autumn animation. Click the sunflower to play a video (full‑screen overlay). A floating hint appears after a few seconds.

## 🛠️ Customization

- **Change dates** – update `REL_START` in the JavaScript (line with `new Date('December 30, 2024 00:00:00')`) and any date ribbons in the month sections.
- **Edit text** – modify the content inside `.detail-text` and month card labels.
- **Replace images** – swap out the `src` in `<img>` tags or keep the same filenames and overwrite the files.
- **Background music** – replace `public/audio/beautiful.mp3` with your own track.
- **VS game opponents** – edit the `OPPONENTS` array in the JavaScript to change images and names.
- **Month 14 animations** – adjust timings, colours, or SVG elements in the CSS and HTML.

## 💡 Credits

- Fonts: [Poppins](https://fonts.google.com/specimen/Poppins) and [Pacifico](https://fonts.google.com/specimen/Pacifico) via Google Fonts.
- Icons: simple SVG paths (home, share, music).
- Sound effects: placeholder files – replace with your own.

## 📝 Notes

This project was made as a gift for a friend's first anniversary. I helped them build it, and they filled it with their personal photos and memories. Feel free to use and adapt it for your own loved ones – just swap out the media and text to make it yours!

---

**Made with 💖 for friends celebrating their love.**
