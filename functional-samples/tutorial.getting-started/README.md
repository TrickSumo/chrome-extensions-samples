# Getting Started with Chrome Extensions

This tutorial will guide you through the basics of creating a Chrome extension. By the end of this tutorial, you will have a simple, functional Chrome extension.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have a basic understanding of HTML, CSS, and JavaScript.
- You have Google Chrome installed on your computer.

## Project Structure

```
tutorial.getting-started/
│
├── manifest.json
├── background.js
├── popup.html
├── popup.js
└── README.md
```

## Steps to Create Your First Chrome Extension

1. **Create the Manifest File**: The `manifest.json` file contains metadata about your extension, such as its name, version, and permissions.

2. **Add Background Script**: The `background.js` file contains the background script that runs in the background and listens for events.

3. **Create Popup HTML**: The `popup.html` file defines the user interface of the popup that appears when the extension icon is clicked.

4. **Add Popup Script**: The `popup.js` file contains the JavaScript code that runs in the context of the popup.

## Loading Your Extension

1. Open Chrome and navigate to `chrome://extensions/`.
2. Enable "Developer mode" by toggling the switch in the top right corner.
3. Click on "Load unpacked" and select the directory containing your extension files.

## Resources

- [Chrome Extensions Documentation](https://developer.chrome.com/docs/extensions/mv3/getstarted/)
- [MDN Web Docs: Extensions](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions)

## License

This project is licensed under the MIT License - see the [LICENSE](../LICENSE) file for details.
