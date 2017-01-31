# [xtria](https://github.com/xtria/new_tg)
*TG-CLI telegram-bot!*

# [mafia](https://github.com/mafia-007/mafia_cli)

https://github.com/mafia-007/mafia_cli

# Install
```
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt-get update
sudo apt-get install g++-4.7 c++-4.7

git clone https://github.com/xtria/new_tg
cd new_tg
chmod +x install.sh
./install.sh
./launch.sh
# Enter a phone number & confirmation code.
##close telminal

cd new_tg
wget https://valtman.name/files/telegram-cli-1215
mv telegram-cli-1215 tg
chmod +x tg
./tg
##close telminal

cd new_tg
screen ./launch.sh
```
```
# Commands
/createsuper name
/id
/ping
/lock links
/mute all
/fwd
/pin
/settings
/view
/username
/echo
/edite text


bot.lua:

tdcli = dofile('tdcli.lua')
redis = (loadfile "./libs/redis.lua")()

sudo_users = {
  284322619,  --id bot
  0
  }
  
 (xtria)
