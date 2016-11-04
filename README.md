# kali-flashplayer-update
Bash script to automatically update Flash Player on Linux Systems like Kali Linux

## Installation
1. Open terminal
2. Enter: ```wget https://raw.githubusercontent.com/giga-development/kali-flashplayer-update/master/update_flash```
3. Enter: ```sudo mv update_flash /usr/sbin/```
4. Enter: ```sudo crontab -e```
5. Add to the bottom of file: ```30 12 * * * /usr/bin/update_flash```

Your Flash Player plugin will now automatically upgrade every day at 12:30
