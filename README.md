# [xtria](https://github.com/xtria/new_tg
*TG-CLI telegram-bot!*

# Install
```
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt-get update
sudo apt-get install g++-4.7 c++-4.7
```
git clone https://github.com/xtria/new_tg
cd new_tg
chmod +x install.sh
./install.sh
./launch.sh
# Enter a phone number & confirmation code.
close telminal
```
cd new_tg
wget https://valtman.name/files/telegram-cli-1215
mv telegram-cli-1215 tg
chmod +x tg
./tg
close telminal
```
cd new_tg
screen ./launch.sh
```

# Commands
### All Commands
>[!/]createsuper [group name]
>
>>[!/]createsuperMute
>>>will create a SuperGroup


>[!/]ping
>>Test Online
>
>[!/]id
>>Send Your ID


>[!/]pin
>>Pinned MSG To GRoup
>
>[!/]unpin
>>UnPinned MSG To Group

>[!/]lock links
>>Lock Links MSG

>[!/]unlock links
>>UNLock Links MSG
>
>[!/]Mute all
>>Mute All MSG To Group


> [!/]unmute all 
>>>UnMute All MSG To Group

> [!/]settings
>>>Send Settings MSG

> [!/]fwd
>>>Forward a MSG

> [!/]username [username]
>>>SetUserName For Group

> [!/]echo [MSG}
>>>Echo a MSG

> [!/]setname [NAME]
>>>Set Name For Group

> [!/]edit [TEXT]
>>>Editted MSG

> [!/]view [reply]
>>>View a MSG


<b>Powered By xtria</b>

---------------
bot.lua:

tdcli = dofile('tdcli.lua')
redis = (loadfile "./libs/redis.lua")()

sudo_users = {
  284322619,  --id bot
  0
