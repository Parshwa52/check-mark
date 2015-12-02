# Bridge Client

Right now it's a Google Chrome extension, but since it's based on React.js + Redux, it can be ported to other web platforms.

## Structure

- `src/app`: React cross-browser application.
- `src/browser`: sources for the extension and Chrome app.

## How to build

* Copy `config.json.example` to `config.json` and define your configurations
* `npm install`
* `npm run build:extension`

## How to develop

* The theme files (SASS files) are under `src/app/styles`
* Other development files are under `src/app/`
* In order to reflect your changes, run `npm run build:extension`

## How to use

* Go to Google Chrome / Chromium
* Type `chrome://extensions`
* Hit "Load unpacked extension..."
* Choose the `build/extension` directory
* An icon will be added to your Google Chrome toolbar

## TODO

Check `TODO.txt`.
