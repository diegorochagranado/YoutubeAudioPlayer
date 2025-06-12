# YouTube Audio Player

A lightweight web-based YouTube audio player that plays the **audio only** from a YouTube video. Built using the official YouTube IFrame Player API with a visually hidden video element.

## 🚀 Features

- Paste any YouTube video URL to play its audio
- Clean and minimal UI
- Uses the official YouTube IFrame API
- Fully client-side (HTML + JavaScript)
- Error handling for invalid URLs or failed playback
- Player remains hidden while still functional

> ⚠️ **Note:** Ads may still play before or during playback, depending on the video and user’s YouTube account status (e.g., Premium vs Free). The player does **not** bypass YouTube ads.

## 📸 Demo

Paste a valid YouTube URL into the input field and click **Play Audio**.

Example:  
`https://www.youtube.com/watch?v=dQw4w9WgXcQ`

## 📦 Usage

1. Clone or download the repo.
2. Open `index.html` in your browser.

Or deploy it online using:
- [GitHub Pages](https://pages.github.com)
- [Netlify Drop](https://app.netlify.com/drop)
- [Vercel](https://vercel.com)

## 🧠 How It Works

- Loads the YouTube IFrame API dynamically
- Extracts the video ID from pasted YouTube URLs using regex
- Initializes an invisible `<iframe>` player
- Loads and plays the video silently (video is visually hidden using CSS)
- Only the audio will be heard

## ✅ Supported URL Formats

Examples of URLs that are supported:

- `https://www.youtube.com/watch?v=VIDEO_ID`
- `https://youtu.be/VIDEO_ID`
- `https://www.youtube.com/shorts/VIDEO_ID`
- `https://www.youtube.com/embed/VIDEO_ID`

## ❌ Limitations

- Cannot skip or block ads (per YouTube's Terms of Service)
- Some videos may be region-locked or unavailable for embedding
- Playback requires the YouTube IFrame API to be ready

## 📄 License

This project is provided for educational purposes only and is **not affiliated with or endorsed by YouTube**. Use responsibly and in compliance with [YouTube’s Terms of Service](https://www.youtube.com/t/terms).

---

Built with ❤️ and JavaScript.


