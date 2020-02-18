# Discord Reposter
Based on Reposter Bot by https://github.com/MysteryPancake
Does the same stuff - except it only posts images for logging purposes.

## GUIDE ON SETTING BOT UP & LOCAL USE
Make a Discord bot [here](https://discordapp.com/developers/applications/)
Copy the token and paste it in Line 9 in `reposter.js` instead of `process.env.token`

As for the setup, follow what this text says at the bottom and install any missing dependencies.
I used the Windows 10 Linux Kernel (bash). 
Enable it by following [this guide](https://www.howtogeek.com/424886/windows-10s-linux-kernel-is-now-available/)
Or download Ubuntu from the Windows 10 Store.
 
*Also highly suggested is using [GIT Bash](https://git-scm.com/downloads) for all your CMD needs*


## CUSTOM STATUS
Edit `client.user.setActivity()` in Line 12 and Line 41 of `reposter.js`
Replace the part in "" with whatever should be after "Watching" on the status. You can also turn it to "Playing".

## DEPLOYING BOT TO HEROKU
I suggest uploading it to Heroku by following their instructions on deploying.
[This video](https://www.youtube.com/watch?v=d8INsGl28xw) is also a good tutorial.
I recommend running all commands with `sudo` and always using Git BASH on the bot folder (`shift + right click`)
Also upload directly to HEROKU with the instructions they give. DONT use the method 'From GitHub' that the dude uses.

## Commands
### Repost To
*Reposts to a channel.*

`/repost <CHANNEL>` or `/repost to <CHANNEL>`

### Repost From
*Reposts from a channel.*

`/repost from <CHANNEL>`

### Repost Webhook
*Reposts through a webhook.*

`/reposthook` or `/repostwebhook` instead of `/repost`

### Repost Live
*Reposts messages as they come.*

`/repostlive` or `/repostlivehook` instead of `/repost`

### Repost Stop
*Stops reposting.*

`/repost stop` or `/repost halt` or `/repost cease` or `/repost terminate` or `/repost suspend` or `/repost cancel` or `/repost die` or `/repost end`

### Repost Commands
*Posts the command list.*

`/repost help` or `/repost commands`

### Repost Replace
*Replaces text when reposting.*

`/repost replace <FIND> <REPLACE>`

### Repost Replacements
*Posts the replacement list.*

`/repost replacements`

### Repost Prefix
*Changes the bot prefix.*

`/repost prefix <PREFIX>`

### Repost Tags
*Toggles user tags when reposting.*

`/repost tags` or `/repost tags <STATE>`

### Repost Nicknames
*Toggles nicknames when reposting.*

`/repost nicknames` or `/repost nicknames <STATE>`

### Repost Pins
*Toggles pins when reposting.*

`/repost pins` or `/repost pins <STATE>`

## Setup
1. [Create your app with a Bot](https://discordapp.com/developers/applications/me).
2. Copy your bot's secret token and [paste it on this line](https://github.com/MysteryPancake/Discord-Reposter/blob/master/reposter.js#L9).
3. Go to `https://discordapp.com/oauth2/authorize?client_id=<CLIENT_ID>&scope=bot`, with `<CLIENT_ID>` as your app's client ID.
4. [Install Node.js](https://nodejs.org/en/download): `brew install node`
5. [Install the dependencies](https://github.com/MysteryPancake/Discord-Reposter/blob/master/package.json#L36-L38): `npm install`
6. [Run the bot](https://github.com/MysteryPancake/Discord-Reposter/blob/master/reposter.js): `npm start`
7. Hope it works!

![Icon](repost.png?raw=true)
