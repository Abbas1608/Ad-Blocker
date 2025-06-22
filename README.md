# AD SHIELD - Ad Blocker Extension

**AD SHIELD** is a lightweight and efficient browser extension designed to enhance your web browsing experience by blocking unwanted ads. It filters out image ads, video ads, popup ads, and other intrusive content using a JSON-based API of known ad URLs. Whether you're browsing news sites or streaming video content, AD SHIELD ensures a cleaner, faster, and distraction-free experience.

---

##  Features

- ✅ Blocks image ads, video ads, and popups
- ✅ Detects and filters ad content via URL-based matching
- ✅ Supports blocking of content ads, inline ads, and overlay banners
- ✅ JSON-based rule engine for easy updates
- ✅ Lightweight and easy to install
- ✅ Compatible with major browsers (Chrome, Edge, etc.)

---

## Tech Stack

- **JavaScript** – Core logic for filtering and blocking
- **JSON** – Ad URL patterns and rule definitions
- **Manifest V3** – Chrome Extension API
- **HTML/CSS** – Popup UI

---

##  How It Works

AD SHIELD uses a content filtering mechanism powered by a JSON ruleset. It intercepts browser requests and blocks those matching known ad-serving domains or URLs.

1. The extension loads a list of ad URL patterns from a JSON file.
2. It uses `chrome.webRequest` API to monitor network activity.
3. Requests matching the ad rules are canceled before content is loaded.

---
## UI Design 
![]()
---

## Conclusion
AD SHIELD is a reliable, easy-to-use ad-blocking extension built for users who value a fast, clean, and safe browsing experience. 
By blocking unnecessary ad content and using a modular JSON ruleset, it ensures continuous improvements and easy updates.
Whether you're looking for fewer distractions or better performance, AD SHIELD delivers.

