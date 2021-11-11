# Weatherscan Simulator
Weatherscan simulation in HTML/JS/CSS

Special thanks to Jessecar, luesjo12, and AnonChickenWalker for orginial development of the simulator. Also special thanks to Josh Nickels for help with finding orginial images.

## Running locally
1. Download & Install [node.js LTS](https://nodejs.org/en/)
2. Get weather.com and mapbox.com API keys.
3. Navigate to `/webroot/js` and create `secrets.js`.
4. Open `secrets.js` and type `var api_key = 'YOUR_API_KEY'`. Replace YOUR_API_KEY with the weather.com API key.
5. On a new line, type `var map_key = 'YOUR_API_KEY'`. Replace YOUR_API_KEY with the mapbox.com API key.
6. In terminal, run `npm install --production` in the root folder of this project. This will install any dependencies.
7. In terminal, run `npm start` in the root folder of this project. This will start a local web server.
8. Follow the link in the console output.

## Development
This project no longer uses gulp to compile SASS to CSS. Just pure CSS.
