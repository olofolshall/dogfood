# dogfood
Homeassistant automation with a zigbee button when dogs have been feed

This project ended up as a nessiceity when I was back home visiing my dad in the US. We have two dogs and every moring in the group chat there was "Did someone feed the dogs already?"; and I thought there needed to by a better way of dealing with this. Homeassitant was the perfect platform since it was already installed and with a cheap zigbee button there could be a physical interface too!

## Project Objectives
1. Know if the dogs have been fed
2. Remind us to feed the dogs if they haven't?
3. Work for both moring and evening feeding 


## Setup
I have included the code for my automations; easiest for you is proably just to create a new automation (three needed; they could proably be combined) and choose edit in YAML then paste my yaml code into it. For this automation to work you need to create a counter helper (found in the helpers in settings menu) which I named "Dog Food Counter" which will keep track of the status. The button I used is the Aqara Wireless Mini Switch (https://a.co/d/bB81S46) and it has worked well for about 6 months so far but feel free to use whatever you have or can by setup might vary a little. I have a screenshot folder, where I have uploaded how it looks for me. 
