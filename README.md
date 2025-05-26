# New Tab Firefox Extension
A minimalistic Firefox extension that replaces the default new tab page with a custom design featuring bookmarks, quotes, and the current date.

Features

- Clean and responsive layout
- Current date and time
- Quick access search form for popular websites
- Quick-access bookmarks to popular websites
- Random quote every time you open a new tab or refresh the page

## Requirements
- Firefox browser

## Setup
```
git clone https://github.com/mariosevripidou/new-tab-firefox-extension
cd new-tab-firefox-extension
```

## Installation
1. Open Firefox and go to about:debugging.
2. Click "This Firefox".
3. Click "Load Temporary Add-on".
4. Select the manifest.json file from the cloned folder.

The custom new tab page should now be active.

## Files
- index.html – Main layout of the new tab
- css/main.css – Styling for the tab
- js/quotes.js – Script to show random quotes
- js/showdate.js – Script to show date and time
- img/main.jpg – Background image
- icons/ – Bookmark icons
- manifest.json – Extension configuration
- icon.png – Extension icon

## Notes
- You can personalize the icons or links in index.html.
- Quotes can be modified in js/quotes.js.
