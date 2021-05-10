# Pomeranian Chihuahua

## Description

An HTML starter using PostCSS and TailwindCSS.

## Why use this starter?

One of my development goals is to eliminate as many steps between initial project ideation and actually building the damn thing. There's plenty of starters out there, however the goal of this starter is to be as lightweight as possible and have the project exist in development the same as it would in production, no need to overcomplicate things.
## Installation

Simply run `npm i` to install all necessary packages. This starter currently uses:

```bash
  "dependencies": {
    "@fullhuman/postcss-purgecss": "^4.0.3",
    "autoprefixer": "^10.2.5",
    "cssnano": "^5.0.2",
    "postcss-cli": "^8.3.1",
    "tailwindcss": "^2.1.1",
    "watch": "^1.0.2"
  },
  "devDependencies": {
    "concurrently": "^6.0.1",
    "cross-env": "^7.0.2",
    "live-server": "^1.2.1"
  }
```
## Using this starter

This starter comes with it's own live-server package so to get up and running locally simply run `npm run serve`. Running `serve` sets up a local live-server instance at port `8080` while also watching for markup or style changes applied to any `.html` files in root, and changes made in the `assets/css` directory.

If you have a preferred, or are using your own, local live server tool simply run your server and use `npm run watch` to just watch for changes in any `.html` file and changes made in the `assets/css` directory.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
