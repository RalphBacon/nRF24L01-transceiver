#nRF24L01 Transceiver
Use your Arduino to transmit (and receive) data reliably with this easy to use module. See the accompanying video #73 here: https://www.youtube.com/c/RalphBacon

There is often a need to transmit data either from or to your Arduino in a reliable manner. The nRF24L01 module achieves this beautifully - and with the excellent RF24 library from TMRh20 we can do just about anything you might think of.

However, in this absolute beginners' guide we just scratch the surface but still managed to produce a useful transmit and receive sketch (originally taken from the above library but simplified even further).

The library I used, very mature, s/he has several others too. See his/her homepage here, choose the RF24 library as I showed in the video. 
https://github.com/TMRh20 <--- Unzip and place in your usual Arduino libraries folder (renamed to RF24).

Note that there are several good nRF24L01 libraries available out there. If you use another one bear in mind that the pin connections will be different. I chose this one as it seemed to give us Arduinites a decent interface to the nRF24L01 module without too much mucking around.

My sketches (one for receive, one for transmit) even though both do actually transmit anyway (remember that each module will automatically acknowledge receipt of data unless you specifically switch off that capability - why would you do this?).

https://github.com/RalphBacon/nRF24L01-transceiver  <--- click the "Clone or Download" button and choose the zip file, unzip and place each sketch in its own folder (of the same name) in your usual Arduino sketches folder.


If you like this video please give it a thumbs up, share it and if you're not already subscribed please do so :)

My channel is here:
------------------------------------------------------------------
https://www.youtube.com/c/RalphBacon
------------------------------------------------------------------ 
How can I remember this? Memory tip: "See" Ralph Bacon, geddit?
