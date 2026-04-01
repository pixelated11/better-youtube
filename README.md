# Better Youtube
... Is a multiplatform youtube client, that is built on electron, and uses adblocker, and userscript to increase user satisfaction when using it.
Supports Windows, Linux AppImage, and Debian installer.
## Features
- @ghostery/electron-adblocker adds adblocker support to this electron app.
- Return Youtube dislike userscript

## Downloading binaries
You can download binaries from the releases page in this repository.

## Building the app
**Dependencies:**
- Node.js 18.0+
- Npm 8+
- Wine (For building windows executable on linux ONLY)
If you want to build the app, first, clone the repository:
```
git clone https://github.com/pixelated11/better-youtube.git && cd better-youtube
```
Then, run this to install Npm dependencies:
```
npm install
```
Then, build the app:
**For linux:**
```
npm run build:linux
```
**For Windows:**
```
npm run build:windows
```

## Running it directly
If you want to run the app directly, without building anything, simply run:
```
npm run start
```
To start the application. Run this in the repository directory.

## Contributing
Contributions are always welcome. Don't hestitate to contact me at itspixelatd@proton.me
Consider starring the repo!
