
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

## Embed

```
const Discord = require("discord.js");
const client = new Discord.Client();
require("discord-replys");

client.on('message', async message => {
  if (message.content === "sykocoder") {

  let embed = new discord.MessageEmbed()
  .setTitle("SykoCoder | İnline Reply Message")
  .setDescription(`Test Reply Message`)


    message.reply(embed)//Mention Reply

    message.replyNoMention(embed)//No Mention Reply
  }

});
 ```

 ## Installation

```
npm i discord-replys
```
