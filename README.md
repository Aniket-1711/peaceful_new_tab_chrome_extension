# 🕊️ Peaceful New Tab Extension

> A beautiful, personalized Chrome new tab experience with nature-inspired backgrounds, motivational quotes, dynamic greetings, and adorable animated pets 🐾 
> [🌐 Live Demo on Vercel](https://peacefulnewtabchromeextension.vercel.app/)

## ✨ Features

- 🌄 **Dynamic Backgrounds** Nature, planets, stars, moon, earth, cricket, forests, mountains, and more — fetched from the [Pexels API](https://www.pexels.com/api/).  
  *(You can replace with your own API key in `script.js`)*

- 💬 **Motivational Quotes** Get inspired every time you open a new tab with a new quote.

- 👋 **Time-based Greetings** Custom greetings like *Good Morning Aniket!* based on the current hour.

- 🐶 **Roaming Pets** Animated emoji pets that follow you around — even across websites!  
  *(You can enable/disable them via the extension settings)*

- 📌 **Top Sites as Buttons** A neatly styled button-based quick-access layout for your top websites.


## 🛠️ How to Use

1.  **Download the Extension** Download the repo ZIP or clone it.

2.  **Load Unpacked Extension in Chrome** - Go to `chrome://extensions/`  
    - Enable **Developer Mode** - Click **Load Unpacked** and select the `peaceful-new-tab-extension` folder

3.  **Replace API Key** In `script.js`, replace the placeholder Pexels API key with your own:
    ```js
    const API_KEY = "YOUR_PEXELS_API_KEY";
    ```

4.  **Enable Bookmarks Bar** Bookmarks will show in the new tab if enabled: Press `Ctrl + Shift + B` or enable from Chrome’s 3-dot menu → Bookmarks → Show Bookmarks Bar.

5.  **Toggle Pets on All Sites** Roaming emoji pets appear even across websites. (Settings toggle UI coming soon!)

## 🚀 Technologies Used
- HTML, CSS, JavaScript
- Pexels API – for backgrounds
- Quote Array – for quotes

## 📦 Deployment
- Deployed via Vercel: [PeacefulNewTabChromeExtension.vercel.app](https://PeacefulNewTabChromeExtension.vercel.app)
- Each commit pushed to the `peaceful-new-tab-feature` branch automatically deploys a new version.

## 💡 Future Enhancements
- Add dark mode
- User preferences persistence (`localStorage`)
- Weather integration
- Pet interactions and sounds
- Customizable quick links

## 🙌 Contributing
Pull requests are welcome! Want to add features like dark mode, more pet types, or cool animations? Fork it and go wild 🌟

## 📝 License
This project is licensed under the MIT License.

## 📬 Contact
For suggestions or feedback, feel free to raise an issue or reach out!
