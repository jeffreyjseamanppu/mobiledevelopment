# PWA - Module 3

# Progressive Web Application (PWA) Demo App

This is a simple Progressive Web Application (PWA) designed for demonstration purposes. It showcases essential PWA features such as offline functionality, fast loading, and home screen installation.

## Features
- **Offline Support**: The app uses a service worker to cache resources, enabling it to function without an internet connection.
- **Fast Loading**: Resources are pre-cached to ensure quick load times.
- **Installable**: Can be added to your device's home screen for an app-like experience.

## How to Use
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/pwa-demo-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pwa-demo-app
   ```
3. Open the project in a local development server. You can use tools like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) or Python's built-in HTTP server:
   ```bash
   python -m http.server
   ```
4. Visit the app in your web browser at `http://localhost:8000` (or the appropriate port).

## Project Structure
```
├── index.html          # Main HTML file
├── styles.css          # Stylesheet for the app
├── service-worker.js   # Service Worker for caching
├── manifest.json       # Web App Manifest
```

## Installation on Home Screen
1. Open the app in your browser.
2. Click the browser's menu (three dots in Chrome) and select "Add to Home Screen."
3. Follow the prompts to install the app.

## Offline Demo
1. Open the app in your browser.
2. Turn off your internet connection.
3. Refresh the page, and observe that the app still works!

## Customization
Feel free to customize the app by editing the following files:
- **`index.html`**: Modify the content or structure of the app.
- **`styles.css`**: Adjust the appearance of the app.
- **`service-worker.js`**: Add or change caching strategies.
- **`manifest.json`**: Update app metadata, such as name, icons, and theme color.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

Enjoy exploring the power of Progressive Web Applications!
