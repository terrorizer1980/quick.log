

Quick.log-discord
========


<div align="center">
    <p>
        <a href="https://discord.io/PlexiDev"><img src="https://discordapp.com/api/guilds/343572980351107077/embed.png" alt="Discord Server" /></a>
        <a href="http://www.youtube.com/subscription_center?add_user=TrueXPixels"><img src="https://img.shields.io/badge/Subscribe-YouTube-red.svg" alt="YouTube Channel" /></a>       
    </p>
</div>

**Note:** This package is under development and will be updated frequently.

**Now supports markdown in `.send`!** [Example](https://i.imgur.com/Z3fPxPh.gif)

This package is meant to provide an easy way view and send logs to a webpage.
You can view our Trello roadmap [here](https://trello.com/b/rRZ6i1Qh)!

**Installation**
```
npm install quick.log-discord
```

**Require Package**
```
var log = require('quick.log-discord')
```

**Webpage Viewable**
```
localhost:8080
```

**Contributions**
*Thank you,*
*Morfixx - General Bugtesting & New Feature Ideas*

## Usage

**Send Log**
```js
log.send('message')
```

**Example** [Output](https://i.imgur.com/Z3fPxPh.gif)
```js
const log = require('./index.js')

log.send('#Supports Markdown!')
log.send('##Updates in real-time!')
log.send('###Viewable from any browser!')

// Counter
let i = 0

let func = setInterval(function () {

    // Send Message
    log.send(`**${i}** | *Random #* = \`${Math.random()}\``)

    i++
}, 500)
```

## Projects Using quick.log
[Infinitude](https://discordbots.org/bot/346516120322179072) **-** A fully customizable, modular, multi-use discord bot. **-** By *TrueXPixels*