# Node-Red-Denon


Hi,

The Denon implementaion of Alexa is not so good and i want more control of the receiver with my voice. Volume up and down, changing input channels aso.

## Dependencies:


[node-red-contrib-denon](https://flows.nodered.org/node/node-red-contrib-denon)

[node-red-contrib-virtual-smart-home](https://flows.nodered.org/node/node-red-contrib-virtual-smart-home)

[node-red-contrib-alexa-remote2-applestrudel](https://flows.nodered.org/node/node-red-contrib-alexa-remote2-applestrudel)



## Additonal Information:

My Denon Receiver is a AVR-X3700H.  You can control it via Telnet and Webinterface.

For my implementation i use the Denon AVR-Control Protocol.

I think it works also with other Denon AVR Models.

----------------------------------------------------

![Zwischenablage_12-02-2024_01](https://github.com/user-attachments/assets/caa911ca-650d-4a0c-a91f-43af3001b490)



How it works:

If you say: "Alexa, turn Denon on"  -->   Denon Receiver is switched on and set volume to 20<br>

If you say: "Alexa, switch Denon input to ..." -->   Denon Receiver is switched the input channel ...  (in my example TV, Game, PC , Bluetooth)<br>

If you say: "Alexa, switch Denon volume to ..." --> Denon Receiver is set to Volume ... (i implement 0 - 70)<br>
                                             
If you say: "Alexa, turn Denon off" -->   Denon Receiver is switched off<br>


-----------------------------------------------------------------------
If you want to use it: have fun with it.

Torsten
