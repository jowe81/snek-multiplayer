# Modified Lighthouse Labs' Snake Server
This is Johannes' fork of [snek](https://github.com/lighthouse-labs/snek-multiplayer) from Lighthouse Labs, which in turn is based on [snek](https://github.com/taniarascia/snek) by [Tania Rascia](https://www.taniarascia.com).

I have added broadcast support for logon/logoff events, which my [snake client](https://github.com/jowe81/snake-client) takes advantage of.

Original README follows below below.

---

# 🐍 Snek.js [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) [![snekjs on NPM](https://img.shields.io/npm/v/snekjs.svg?color=green&label=snekjs)](https://www.npmjs.com/package/snekjs)

A terminal-based Snake implementation written in JavaScript (Node.js).

![snek.gif](https://raw.githubusercontent.com/taniarascia/snek/master/snek.gif)

## Instructions

To play the game, one needs to implement a game client. An example solution code for the client can be [found here](https://github.com/lighthouse-labs/snek-client) (it's a private repository, not accessible to everyone).

## Installation

### Clone from repository

```bash
git clone https://github.com/lighthouse-labs/snek-multiplayer.git
cd snek-multiplayer

# install and run via npm
npm install
npm run play
```

## Acknowledgements

This project was not built from scratch. It was inspired and started from [snek](https://github.com/taniarascia/snek) ([blog post](https://www.taniarascia.com/snake-game-in-javascript/)). [Tania Rascia](https://www.taniarascia.com) is the original author.

## License

This project is open source and available under the [MIT License](LICENSE).
