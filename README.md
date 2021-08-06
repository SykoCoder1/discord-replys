
**Discord Replys | SykoCoder**

**Site:** https://sykocoder.tk

**NPM:** https://npmjs.com/package/discord-replys

**Bug Report:** SykoCoder#4105

## Example

```
const Discord = require("discord.js");
const client = new Discord.Client();
require("discord-replys");

client.on('message', async message => {
  if (message.content === "sykocoder") {
    message.reply("SykoCoder")//Mention Reply

    message.replyNoMention("SykoCoder")//No Mention Reply
  }
});
 ```

 ## Installation

```
npm i discord-replys
```
