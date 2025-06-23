Not entirely sure who the original creator was, but I picked it up from user wryandginger in the community Home Assistant post here https://community.home-assistant.io/t/esp32-a1s-audio-kit-media-player/522245 which I then modified and improved upon making it a complete solution.

ESP32-Audio-Kit is an ESP32 A1 Module placed on an Audio Board with 8x Programmable Buttons. It provides an Audio In (Microphone) and Audio Out (Aux) Jack along with a speaker jack for using a small 8 ohm 3W speaker (mono or stereo). The board can also be battery powered with it's own built in charge controller (battery management).

I should add that the 'Microphone In' jack doesn't function correctly because of the resistor layout on the board. Therefore no implementation of the microphone is done on this board. In addition, aside from patching it through to the Aux Out (or plugged in speaker) I'm not sure what else it could be used for (the patch through though is interesting) since getting an audio stream through the ESP32 and into Home Assistant is (at the moment) beyond me.

