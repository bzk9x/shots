# Shots (Unofficial Desktop Port)

This is an unofficial desktop port of shots.so website using Electron.

## DISCLAIMER

This application is a fan-made port of the original website shots.so. This is NOT an official product and is not affiliated with, endorsed by, or connected to the original shots.so website or its creators.

This is a free, unofficial port created by fans for educational and demonstration purposes only. All rights and trademarks belong to their respective owners.

By installing and using this application, you acknowledge that:
1. This is an unofficial, fan-made port
2. This is not affiliated with the original shots.so website
3. This is created for educational purposes only

Please visit shots.so for the official web application.

## How It Works

This application is a simple Electron wrapper around the shots.so website. It works by:
1. Creating a desktop window using Electron
2. Loading the shots.so website within an iframe
3. Providing a native desktop experience for the web application

The core functionality is implemented in `screen_home.html`, which embeds the shots.so website:
```html
<iframe src="https://shots.so/" frameborder="0"></iframe>
```

## Development
To run the application locally:
```bash
npm install
npm start
```

To build the application:

```bash
npm run package-win
```

## Credits
All credits for the functionality and content go to the original shots.so website and its creators.