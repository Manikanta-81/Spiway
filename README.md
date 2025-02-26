# Spiway Web Page

This is a simple landing page for the **Spiway** app, featuring navigation, services, and an app access button that redirects users to the appropriate store based on their device.

## Features
- Responsive navigation bar with a toggle menu for mobile devices.
- Services section displaying various services offered by Spiway.
- A button to access the Spiway app on Android and iOS.
- Mobile-friendly design using CSS media queries.

## Technologies Used
- **HTML** for structuring the webpage.
- **CSS** for styling and layout.
- **JavaScript** for handling menu toggle and app redirection.

## Installation & Usage
1. Clone this repository or download the files.
2. Open `index.html` in a web browser.
3. To modify styles, edit `styles.css`.
4. The JavaScript logic for app redirection is in the `<script>` tag within `index.html`.

## App Access Button Logic
The button detects the user's device and redirects them accordingly:
- **Android** → Google Play Store link
- **iOS & Mac** → Apple App Store link
- **Other devices** → Google Play Store link as a fallback

## Code Structure
```
/spiway-website
│── index.html         # Main HTML file
│── styles.css         # CSS file for styling
│── script.js          # javascript file
│── README.md          # Project documentation
```

## Future Enhancements
- Add a real iOS App Store link when available.
- Improve the mobile responsiveness further.
- Optimize images for faster loading.
