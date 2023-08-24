# ADMute-Ad-Blocker
A minimalistic Ad blocker Chrome Extension

# Simple Ad Blocker Chrome Extension

## Overview

The Simple Ad Blocker is a Chrome extension designed to enhance users' browsing experiences by effectively blocking intrusive advertisements. This repository contains the source code and configuration files for the extension, which leverages Chrome's built-in capabilities to provide users with a cleaner and more focused online environment.

## Features

- **Efficient Ad Blocking**: The extension utilizes the `declarativeNetRequest` permission to efficiently filter and block intrusive ads on websites. This improves page loading times and overall browsing performance.

- **User-Friendly Design**: The extension's interface is minimalistic and unobtrusive, allowing users to enjoy a seamless browsing experience without unnecessary distractions.

- **Customizable Rules**: The `rules.json` file contains a set of curated rules that specify which ad-related URLs to block. Users can customize these rules to tailor the extension's behavior according to their preferences.

- **Selective Domain Blocking**: The example rules provided in the `rules.json` file demonstrate how to block domains such as `doubleclick.net` and `googleadservices.com`. This illustrates how the extension can effectively target specific ad-serving platforms.

## Installation

To install the Simple Ad Blocker Chrome extension, follow these steps:

1. Clone this repository to your local machine or download the source code as a ZIP file.

2. Open Google Chrome and navigate to `chrome://extensions/`.

3. Enable "Developer mode" by toggling the switch in the upper-right corner.

4. Click the "Load unpacked" button and select the folder containing the cloned/downloaded extension files.

5. The Simple Ad Blocker extension will now be added to your Chrome browser.

## Configuration

The extension's behavior can be customized by modifying the `rules.json` file. This file contains an array of rules that dictate which URLs should be blocked. Rules can be added, modified, or removed to adapt the extension to your preferences.

## Contributing

Contributions to this project are welcome! If you have ideas for improvements, bug fixes, or additional features, please fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

The Simple Ad Blocker Chrome extension was created by Janhavi. Special thanks to the developers of the `declarativeNetRequest` API and the libraries used in this project.



---

**Disclaimer:** The Simple Ad Blocker extension is designed for personal use and is not intended to violate website terms of service or infringe on content creators' rights. Use this extension responsibly and consider whitelisting websites that rely on non-intrusive advertisements for revenue.
