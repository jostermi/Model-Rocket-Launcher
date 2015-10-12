# Model-Rocket-Launcher
All of the code for the Make it Great Rocket Launcher project. 
First in the webiopi config file /WebIOPi/python/config file and change the doc-root to be where you download the 
model-rocket-launcher file. 
set the welcome-file to rocket.html 
in rocket.html set the appropiate GPIO port. I used 18
to start webiopi "sudo webiopi -c ~/WebIOPi-0.7.1/python/config"
The browse to http://ip_address_of_your_Pi:8000 and press launch. It should be red which means it is off
when you press the button it will turn to black which means the GPIO interface is on. 
