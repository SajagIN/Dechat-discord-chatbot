<h1 align="center">Welcome to Dechat Chatbot 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/SajagIN/Dechat-discord-chatbot#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/SajagIN/Dechat-discord-chatbot/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://github.com/SajagIN/Dechat-discord-chatbot/blob/master/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/github/license/SajagIN/dechat-discord-chatbot" />
  </a>
  <a href="https://twitter.com/codewhiteweb1" target="_blank">
    <img alt="Twitter: codewhiteweb1" src="https://img.shields.io/twitter/follow/codewhiteweb1.svg?style=social" />
  </a>
</p>

> A Simple Discord Chatbot Created by Codewhiteweb

### 🏠 [Homepage](https://github.com/SajagIN/Dechat-discord-chatbot#readme)

### ✨ [Parameter Gist](https://gist.github.com/SajagIN/af80da4c1942f6a5df7118a3f64ea363)

## Install

```sh
npm install
```

## Usage Instruction
- add your bot token to `.env.example` file and rename it to `.env`
- install dependency by running `npm i` or `yarn`
- customize your bot settings in ` index.js`
- go to `line 30` on `index.js` file and edit it
```js
    const chat = new Chat({
      user: uid, // required DO NOT REMOVE
      name: "Chatari",//name of bot
    });
```
- add more parameters from your choice [ALL PARAMETERS LIST](https://gist.github.com/SajagIN/af80da4c1942f6a5df7118a3f64ea363)
```js
    const chat = new Chat({
      user: uid,                      // required DO NOT REMOVE
      name: "Chatari",                // name of bot
      developer_name: "CodeWhiteweb", // your name
      age: "1 year",                  // bot's age
      color:"Blue"                    // bot's favourite color
      
      // you can extend the option with all possible parameters from the link given above
    
    });
```
## Run It

```sh
npm start
```

## Author

👤 **SajagIN**

* Website: https://SajagIN.cf
* Twitter: [@codewhiteweb1](https://twitter.com/codewhiteweb1)
* Github: [@SajagIN](https://github.com/SajagIN)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/SajagIN/Dechat-discord-chatbot/issues).

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2022 [SajagIN](https://github.com/SajagIN).<br />
This project is [MIT](https://github.com/SajagIN/Dechat-discord-chatbot/blob/master/LICENSE) licensed.
