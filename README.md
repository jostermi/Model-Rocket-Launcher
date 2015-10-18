# Model-Rocket-Launcher
All of the code for the Make it Great Rocket Launcher project. 
First in the webiopi config file /WebIOPi/python/config file and change the doc-root to be where you download the 
model-rocket-launcher file. 
set the welcome-file to rocket.html 
in rocket.html set the appropiate GPIO port. I used 18
first execute sudo ~/Model-Rocket-Launcher/script.py
to start webiopi "sudo webiopi -c ~/WebIOPi-0.7.1/python/config"
The browse to http://ip_address_of_your_Pi:8000 and press launch. It should be red which means it is off 
when you press the button it will turn to black which means the GPIO interface is on. 
LaunchAll.html allows for 8 buttons. this is perfect if you have a lot of kids that each want to light off their own rocket
http://ip_address_of_your_Pi:8000/LaunchAll.html
You will probably want webiopi and script.py to run a start. If so look at the following link for what will work for you. http://raspberrywebserver.com/serveradmin/run-a-script-on-start-up.html

