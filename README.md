
# CSS Grid & Web-MIDI Demo 
An (simple) demo of the new CSS grid & Web-MIDI APIs.  Complete with a cyberpunk color scheme.

### Usage:
- Open up index.html (all the css and javascript is included already in index.html for convenience).
- Click on buttons (to send MIDI note on or off messages).
- Click the slider and move the mouse around (to send MIDI CC messages 12 & 13 for the x and y axis respectively).

### Issues:
- Web-MIDI __only works__ in Google-Chrome currently.
- MIDI data is sent out on whatever the first device returned by the Web-MIDI API happens to be (ALSA's midi-through on my linux system).
- Sound will not be generated, *only* MIDI data.  A hardware or software synthesizer must be running to reify sound.
