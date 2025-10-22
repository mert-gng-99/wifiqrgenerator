# WiFi QR Code Generator

A simple web application to generate a QR code for connecting to a WiFi network. Users can enter their network name (SSID) and password, and the app will instantly generate a scannable QR code. This allows anyone to connect to WiFi by simply pointing their phone’s camera at the screen or printed card.

## Table of Contents

* [Features](#features)
* [Demo](#demo)
* [Installation](#installation)
* [Usage](#usage)
* [Dependencies](#dependencies)
* [Configuration](#configuration)
* [Examples](#examples)
* [Styling](#styling)
* [Troubleshooting](#troubleshooting)
* [Contributors](#contributors)
* [License](#license)

---

## Features

* 🔐 Enter SSID and password to generate WiFi QR code
* 📸 Instant QR code preview
* 🖨️ Print-ready layout
* 🖌️ Clean and responsive design
* 🧠 Auto-updates QR code as you type

---

## Demo

Live demo: *[Not deployed – you can deploy it on GitHub Pages, Netlify, or Vercel]*
Or simply open `index.html` in your browser.

---

## Installation

1. Clone this repository or download the ZIP.
2. Open the `index.html` file in any modern browser.

```bash
git clone https://github.com/mert-gng-99/wifiqrgenerator.git
cd wifiqrgenerator
open index.html
```

---

## Usage

1. Enter your **WiFi Network Name (SSID)**.
2. Enter your **WiFi Password**.
3. The QR code updates in real-time.
4. Click **"Print Wifi Card"** to print a card that guests can scan to join your network.

---

## Dependencies

This project uses the following external resource:

* [goqr.me API](https://goqr.me/api/) for generating QR codes:
  `https://api.qrserver.com/v1/create-qr-code/`

---

## Configuration

* The QR code is generated in the format:

  ```
  WIFI:T:WPA;S:<SSID>;P:<Password>;;
  ```

  You can modify the encryption type (e.g., `WEP`, `nopass`) in `script.js` if needed.

---

## Examples

```plaintext
SSID: MyHomeWiFi
Password: Secure1234
↓
QR Code will be generated and embedded automatically
```

---

## Styling

The interface is styled with `style.css`, which includes:

* Centered form layout
* Mobile-responsive adjustments
* Print styles to hide the button when printing

You can customize colors, spacing, and fonts easily within `style.css`.

---

## Troubleshooting

* **QR code not updating?** Ensure JavaScript is enabled in your browser.
* **Printing issues?** Try adjusting print scaling or margins in your browser's print settings.
* **QR code not scanning?** Double-check that the SSID and password are accurate and match the WiFi router.

---

## Contributors

* [Your Name] – Creator & Developer

---

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute it with attribution.

---

Would you like me to help you deploy this online or generate a GitHub-friendly version with badges and links?
