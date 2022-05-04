# About
- A discord.js Utils Package with qrcode and other utility commands! Works With Slash and Normal Commands!

## ✏️ <b>Support Server
<a href="https://discord.gg/HHkuFTy4r4"> <img src="https://discord.com/api/guilds/955029112219664415/widget.png?style=banner2"> </a>

# Example usage

**QR CODE GENERATOR**
=== 
*NORMAL COMMAND*
```js
const { Utils } = require('disc-plexus')
  const util = new Utils({
    args: args[0],
    message: message,
    slashCommand: false,
    embedFooter: "Made With disc-plexus", 
    embedTitle: "Generated A QR Code", 
    embedColor: "RANDOM", 
   })
   util.qrcode()
```
*SLASH COMMAND*
=== 
```js
const { Utils } = require('disc-plexus')
    const util = new Utils({
     args: args,
     slashCommand: true,
     interaction: interaction,
     embedFooter: "Made With disc-plexus", 
     embedTitle: "Generated A QR Code", 
     embedColor: "RANDOM", 
   })
util.qrcode()
```
