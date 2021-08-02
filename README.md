# Auto-File-Forward-Bot

Auto file forward bot.
Without Admin Permission in FROM_CHANNEL
Only Give Permission In your Telegram Personal Channel

```
Please fork this repository don't import code
Made with Python3
(C) @trtechguide
Copyright permission under GNU GENERAL PUBLIC LICENSE
```

### Deploy on Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/TR-TECH-GUIDE/Auto-Forward-Bot)

## HOW TO DEPLOY YOUTUBE TUTORIAL

<a href="Coming Soon"><img src="https://trtechguide.files.wordpress.com/2021/07/untitled-design-2.png"></a>

Deploy in your vps
```sh
git clone https://github.com/TR-TECH-GUIDE/Auto-Forward-Bot
cd Auto-Forward-Bot
pip3 install -r requirements.txt
# <Create Variables appropriately>
python3 main.py
```

### Variables

* `API_HASH` Your API Hash from my.telegram.org
* `API_ID` Your API ID from my.telegram.org
* `BOT_TOKEN` Your bot token from @BotFather
* `OWNER_ID` Must enter Your Telegram Id
* `FROM_CHANNEL` Enter any public channel eg:- @nstcentertainmentgroup
* `TO_CHANNEL` Your Channel ID eg:- -100xxxxxxxx
* `CAPTION` If you want to add a caption to the forwarded file, enter it here
* `FILTER_TYPE` Enter Filter type eg:- document or audio or photo or empty
* `SKIP_NO` Enter File Skiping Number default number '0' 
* `SESSION` Enter Pyrogram session string [String Generator](https://replit.com/@PDTharukRenuja/Pyrogram-String-Session)

