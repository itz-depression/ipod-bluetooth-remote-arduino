# ipod-bluetooth-remote-arduino
ipod bluetooth remote with an arduino




you will need

1x arduino (duh) 
1x apple universal dock remote (a1156 used here others shuld works but do you testing) 
1x level shifter (or you could just make alot of voltage deviders needed to drop the 5v logic down to 3v3 for the remote)
some wire to hook stuff up

guide for a a1156 remote (idk about any others so upto you)

disasemble your universal dock remote idc how you do it just try not to brake the pcb

take off the buttons leaving just the contacts on the pcb

3.solder a wire to the middel contacts to the level shifter 

4.solder a wire to the top battery tab (the one on same side of the buttons) this is for power as the buttons need to be pulled high

solder a wire to the other battery contact

solder from your level shifter to the arduino

change pins in the code to match what pins you solderd to

power the arduino up and run the code

to test if it works you will need to use an app like "arduino bluettoh controler"

now you can controler your ipod via bluetooth yey but was that worth it did you have nothing better to do with your life than to make someting as pointless as this no well same now enjoy
