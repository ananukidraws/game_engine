# game_engine
Simple Game Engine for my projects

## How to play locally
Simple drag the `local.html` file into a browser of your choice!

## Development
Launch `index.html` with a Live Server so you can see changes made in real time. Since it's all JS, the moment you change a file the Live Server should update.

## Modding

Asset modding is simple, just replace the .png and .mp3 files with whatever you want and it'll "Just work":tm:. This applies to even the local copy of the game, no coding required!

## Building a local copy
To build a local version, install Bun from `bun.sh`, navigate to where this file is stored in your terminal of choice, and then type in the following command: `bun build Code/Source/main.js --outfile Code/Local/main.js`

Note: This is done to get around CORS and I'd rather do this than work in a single giant JS file myself.

## Deployment
Zip it up and throw the entire folder at any static site hosting provider you want, nothing else needed!