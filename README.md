# CINEMA KOTTA
##[![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=welcome+To+TEAM-SAZUKI-KERALA-πππ!;created+by+π»π¬π¨π΄+ππ°πππΊπΈ+πΊπ΄ππ°π»π°!;A+simple+autofilter+Bot!;Auto+filter+with+double+button!;start+message+with+pic!;and+all+futures!)
</p>
πππππ πππππ πππ ππππππ ππππππππ

[![Deploy](https://telegra.ph/file/0f4bd95c31535e3ca27ff.jpg)](https://heroku.com/deploy?template=https://github.com/SAZUKI-SAMSUNG/TEAM-SAZUKI-KERALA)
- [x] Auto Filter
- [x] Manuel Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB search
- [x] Fun mode
- [x] Inline Search
- [x] Random pics
- [x] ids and User info 
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel



<h3 align="center">βπβππΈβπ<img align="center" src="https://github.com/SAZUKI-SAMSUNG/TEAM-SAZUKI-KERALA" height="33px" /></h3>
<p align="center">
<a href="https://t.me/pushpa_Reju"><img alt="Telegram" src="https://img.shields.io/badge/π³π΄π 1-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/></a>
<a href="https://t.me/TEAM_KERALA"><img alt="Telegram" src="https://img.shields.io/badge/π³π΄π 2-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/></a>
</p>



## Installation






```bash
# Create virtual environment
python3 -m venv env

# Activate virtual environment
env\Scripts\activate.bat # For Windows
source env/bin/activate # For Linux or MacOS

# Install Packages
pip3 install -r requirements.txt

# Edit info.py with variables as given below then run bot
python3 bot.py
```
Check [`sample_info.py`](sample_info.py) before editing [`info.py`](info.py) file

## Variables

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )
* Check [info.py](https://github.com/EvamariaTG/evamaria/blob/master/info.py) for more

## Note
* Currently [API used](http://www.omdbapi.com) here is allowing 1000 requests per day. [You may not get posters if its crossed](https://t.me/ThankTelegram/910168). 
Once a poster is fetched from OMDB , poster is saved to DB to reduce duplicate requests.

## Admin commands
```
channel - Get basic infomation about channels
total - Show total of saved files
delete - Delete file from database
index - Index all files from channel.
logger - Get log file
```

## Tips
* You can use `|` to separate query and file type while searching for specific type of file. For example: `Avengers | video`
* If you don't want to create a channel or group, use your chat ID / username as the channel ID. When you send a file to a bot, it will be saved in the database.



## Thanks to 
* [Edit Repo](https://github.com/SAZUKI-SAMSUNG/TEAM-SAZUKI-KERALA)
* Original [Repo](https://github.com/SAZUKI-SAMSUNG/TEAM-SAZUKI-KERALA)


## Support
Contact Me On [Telegram](https://t.me/TEAM_KERALA)

[Update Channel](https://t.me/new_movie_cinema_kotta)

## License
Code released under [The GNU General Public License](LICENSE).
## credit π
##[![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=Credit-To-TEAM-KERALA!;)
</p>


[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2FSAZUKI-SAMSUNG%2FTEAM-SAZUKI-KERALA&envs=API_HASH%2CAPI_ID%2CBOT_TOKEN%2CCHANNELS%2CADMINS%2CDATABASE_NAME%2CDATABASE_URI%2CLOG_CHANNEL%2CPICS&optionalEnvs=CHANNELS%2CDATABASE_NAME%2CPICS&API_HASHDesc=Get+this+value+from+telegram.org&API_IDDesc=Get+this+value+from+telegram.org&BOT_TOKENDesc=Create+a+bot+using+%40BotFather%2C+and+get+the+Telegram+API+token.&CHANNELSDesc=Username+or+ID+of+channel+or+group.+Separate+multiple+IDs+by+space&ADMINSDesc=Username+or+ID+of+Admin.+Separate+multiple+Admins+by+space&DATABASE_NAMEDesc=Name+of+the+database+in+mongoDB.+For+more+help+watch+this+video&DATABASE_URIDesc=mongoDB+URI.+Get+this+value+from+mongoDB.+For+more+help+watch+this+video&LOG_CHANNELDesc=A+channel+to+log+the+activities+of+bot.+Make+sure+bot+is+an+admin+in+the+channel&PICSDesc=Telegraph+links+of+images+to+show+in+start+message.%28+Multiple+images+can+be+used+seperated+by+space+%29&referralCode=LBlqTu)
