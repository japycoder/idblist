# idbList
idbList is the lightning-fast, offline-first multi-list shopping and task checklist manager built entirely within a single, highly portable file. Powered by IndexedDB, it brings zero-lag UI updates, smart auto-complete, privacy and zero bloat. Your lists, your device, zero friction!

## ✨ Core Features

- **Offline-First Architecture:** Powered by browser-native `IndexedDB` stores your list on your device.
- **Single-File Portability:** The entire application (HTML5, Tailwind CSS via CDN, FontAwesome 6 icons, and Vanilla ES6 JavaScript) lives inside a single `index.html` file. 
- **Lightning-Fast UI:** Optimistic UI updates ensure instant item toggling and rendering with zero input lag.
- **Smart Auto-Complete Engine:** Real-time lookup against your historical item dictionary, auto-filling both item names and categories.
- **Batch Text Import:** Paste multi-line or comma-separated text to instantiate multiple items simultaneously under a selected category.
- **Clean Data Portability:** Export your lists to clean JSON and import them back in.
- **Social Sharing:** Easily compile active items grouped by category into clean, formatted text optimized for clipboard copying into messaging apps like WhatsApp or iMessage.

## 🌐 Access via GitHub Pages
  You can access **idbList** instantly and free from GitHub Pages:
  https://japycoder.github.io/idblist/
  
## 🚀 Run Locally

Because **idbList** is a single-file application, running it locally requires zero build tools or server configurations:

1. Clone or download this repository.
2. Double-click the `index.html` file to open it directly in any modern web browser.

## 🛠️ Technical Stack

- **Markup & Styling:** HTML5, Tailwind CSS (via CDN)
- **Icons:** FontAwesome 6
- **Scripting:** Vanilla ES6 JavaScript
- **Storage Layer:** IndexedDB (`idb-keyval`)

## 📄 License

This project is open-source and licensed under the [GNU GPLv3](LICENSE).
