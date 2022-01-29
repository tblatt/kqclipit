# kqclipit
twitch clip button
We're making a physical button that sits in the cupholder of a KQ cab. 
You connect it to the internet via wifi by powering the device up, joining the wifi network it creates on your phone or computer.
and then going to 192.168.4.1 and then giving your ssid/pw

the button will send commands to twitch to make a twitch clip of whatever just happened in the game. We're gonna go back 20 seconds or so
we havea  private/public key from twitter oauth to use the twitter api. users will need to have their own twitch account so the clips get saved to that account. 

How does the button know which stream to capture? we give it broadcaster_id


1/4" plywood lasercut files
use the big 50mm arcade button
nodemcu esp8266 1.0 12E
wire 10k ohm resistor from pin 14 to ground
wire 5v/3.3v to button, other lead to pin 14.
button should be Normally Open
