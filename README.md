# TwLocation [![python](https://img.shields.io/badge/Python-2.7-green.svg?style=style=flat-square)](https://www.python.org/downloads/) ![version](https://img.shields.io/badge/Build-Final-blue.svg) ![license](https://img.shields.io/badge/License-GPL_3-orange.svg?style=style=flat-square)

Python script that gets Twitter users' tweets location 


<a href="https://asciinema.org/a/dFXzrdrZmK6ADF2ZQVMse43gg" target="_blank"><img src="https://asciinema.org/a/dFXzrdrZmK6ADF2ZQVMse43gg.png" /></a>

Made with ![heart](https://cloud.githubusercontent.com/assets/4301109/16754758/82e3a63c-4813-11e6-9430-6015d98aeaab.png) by <a href=https://twitter.com/MazenElzanaty>Mazen Elzanaty</a>

## Features
- Gets Twitter Usernames based on a latitude and longitude
- Profiles URLs
- Tweet Latitude and Longitude
- Google Maps link to Latitude and Longitude

## Usage
TwLocation should work on all Linux distros running Python 2.7
First, clone it by entering the following command in the terminal
``` bash
git clone https://github.com/MazenElzanaty/TwLocation.git
```
Now navigate to TwLocation directory
``` bash
cd TwLocation
```
Now install the requirements with the following command
``` bash
pip install -r requirements.txt
```
Edit config.txt and put your twitter app keys
``` bash
cat config.txt
consumer_key = "XxXxXxxXXXxxxxXXXxXX"
consumer_secret = "xXXXXXXXXxxxxXxXXxxXxxXXxXxXxxxxXxXXxxxXXx"
access_key = "XXXXXXXX-xxXXxXXxxXxxxXxXXxXxXxXxxxXxxxxXxXXxXxxXX"
access_secret = "XxXXXXXXXXxxxXXXxXXxXxXxxXXXXXxXxxXXXXx"
```
Now you can run TwLocation
``` bash
python TwLocation.py
```

## Video
[![Thumbnail](https://img.youtube.com/vi/VuCOE8PwJDs/0.jpg)](https://www.youtube.com/watch?v=VuCOE8PwJDs)


