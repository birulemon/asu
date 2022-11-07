# Discord SelfBot

Simple Discord Self Bot Python version

Created By viloid (github.com/vsec7)

*** NOTE : USE AT YOUR OWN RISK! ***

## • Requirements
- Python3

## • Installation

```bash
git clone https://github.com/vsec7/DiscordSelfbot.git
```

## • Edit Configurations *config.yaml* file

```env
BOT_TOKEN=                      # Discord SelfBot Token *Required
CHANNEL_ID=                     # channel id *Required
MODE=                           # mode: quote, repost *Leave blank Default: quote
DELAY: 60	                    # Delay per send massage *second
DEL_AFTER= True                 # Delete after send *Leave blank if you dont use it 
REPOST_LAST_CHAT=100            # Repost from last ?n chat in channel          
```
## • How to get Discord SelfBot Token?

```
javascript:var i = document.createElement('iframe');i.onload = function(){var localStorage = i.contentWindow.localStorage;prompt('DC Token By @github.com/vsec7', localStorage.getItem('token').replace(/["]+/g, ''));};document.body.appendChild(i);
```

Paste in your url bar when open discord desktop browser

word **javascript** may removed by browser , you can type it manual.

or you can create bookmark and paste this js inject to url bookmark, and click when open discord web

## • How to Run?
```bash
cd DiscordSelfBot
python3 bot.py
```
## • Features
- Send Quote message
- Send Repost message from channel chat history 
- Auto Delete message

## • Donation

SOL Address : viloid.sol

BSC Address : 0xd3de361b186cc2Fc0C77764E30103F104a6d6D07