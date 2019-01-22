# telegram-cat-bot
sends you random cats 

``` bash

git clone git@github.com:pocketguy/telegram-cat-bot.git

cd telegram-cat-bot

# make sure to provide your own token
TOKEN='XXX:YYY'

docker build -t hppbrthd2018 .

docker run -d --restart unless-stopped -e "TOKEN=$TOKEN" --name happy2018-run hppbrthd2018

```
