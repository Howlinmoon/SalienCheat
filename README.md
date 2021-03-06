# How to use this

## First steps

1. ~~Join https://steamcommunity.com/groups/SteamDB (needed to represent captures)~~
2. Subscribe to any (or no) Steam Group of your liking.
3. Select PHP or Python version of the script, you don't need both

## PHP

1. Install PHP (yes, really)
   1. Download https://windows.php.net/downloads/releases/php-7.2.7-nts-Win32-VC15-x64.zip
   2. Extract zip to `C:\php`
   3. Open `php.ini-production` in a text editor
   4. Find `;extension=curl` and remove the semicolon
   5. Save as `php.ini`
2. Extract the contents of this script to the same folder
3. Open https://steamcommunity.com/saliengame/gettoken and save it as `token.txt` in same folder as `cheat.php`
4. Run the script: `php cheat.php`

You can also provide token directly in CLI, to ease running multiple accounts: `php cheat.php

## Python

0. (optional) Setup virtual env: `virtualenv env && source env/bin/activate`
1. `pip install requests tqdm` (LINUX/POSIX: install the `python-tqdm` package)
2. Place your token in the script in place of the X's (more reliable on other Operating Systems than the Token File)
3. Run the script: `python cheat.py`
