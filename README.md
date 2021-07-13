# Sarah-Personal-Assistant

<p align="center">
  <img width="" height="" src="https://user-images.githubusercontent.com/63748662/125319690-a6760b00-e343-11eb-9fcc-ddfe102dd2cc.PNG">
</p>

An attempt to make a very simple, Personal Assistant that understands speech as well as text input and is capable of performing tasks. This project is based on pyttsx3 which is a library in Python. pyttsx3 is a text-to-speech conversion library in Python. Unlike alternative libraries, it works offline, and is compatible with both Python 2 and 3. Combined with a few python scripts, Sarah now performs quite a few tasks.

## Installation :
	pip install pyttsx3
> If you get installation errors , make sure you first upgrade your wheel version using :  
`pip install --upgrade wheel`

`If you recieve errors such as No module named win32com.client, No module named win32, or No module named win32api, you will need to additionally install pypiwin32.`
## Installation :


### Linux installation requirements : 
+ If you are on a linux system and if the voice output is not working , then  : 
	Install espeak , ffmpeg and libespeak1 as shown below: 
	```
	sudo apt update && sudo apt install espeak ffmpeg libespeak1
	```
## Modules required to make this project work : 
* pyttsx3
* speech_recognition as sr
* datetime
* wikipedia
* webbrowser
* os
* smtplib
* pyaudio
* re
* pyowm
