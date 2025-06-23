Not entirely sure who the original creator was, but I picked it up from user wryandginger in the community Home Assistant post here https://community.home-assistant.io/t/esp32-a1s-audio-kit-media-player/522245 which I then modified and improved upon making it a complete solution.

![ESP32-Audio-Kit (Generic)](https://github.com/user-attachments/assets/d1006960-926c-4d95-ab4e-ebac3d88dc9c)

ESP32-Audio-Kit is an ESP32 Module placed on an Audio Board with 8x Programmable Buttons. It provides an Audio In (Microphone) and Audio Out (Aux) Jack along with speaker jacks for using small 8 ohm 3W speakers (mono or stereo). The board can also be battery powered with it's own built in charge controller (battery management).

I should add that the Audio In jack (microphone) doesn't function correctly because of the resistor layout on the board (maybe I'll post a detailed picture explaining the problem). Therefore no implementation of the microphone is done on this board. In addition, aside from patching it through to the Aux Out (or plugged in speaker) I'm not sure what else it could be used for (the patch through though is interesting to add an additional 'controllable' audio source) since getting an audio stream through the ESP32 and into Home Assistant is (at the moment) beyond me.
