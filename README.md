# Random Emojis Generator


emojis-random is a Package which generates random Letters.

- Easy to Use.

- You can Customise the random emojis generation.

## Installation

```sh
npm i emojis-random
```

## Usage

Example

```javascript

// This is just an Example you can use the package in anyways

const Discord = require("discord.js");

const randomemojis = require('emojis-random');

const client = new Discord.Client();
 
client.on("message", (message) => {

  if (message.content = "+randomemoji")) {
    message.channel.send(randomemojis(10));

  }
});

client.login("YOUR DISCORD BOT TOKEN");


```



### [Discord Support Server](https://discord.gg/zRqEsZjFj8)