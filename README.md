# Autotel Basic JSFX utils

JSFX utilities I've created for myself, when I've seen the need.

## Channelizer 

Set the channel to all incoming midi, only if the signal is channel-specific. 

## Delay-pan

Pan the audio signal, also delaying it slightly as to simulate the time sound takes to travel a distance. Speed of sound and stereo distance can be adjusted. It's not enough as HRTF, but the effect is still satisfying. For HRTF there are several really good plugins such as IEM suite.

## X/Y PAd

Control stuff with a x/y pad - the idea is that you map your fx or synth params to either of the three sliders, and then control those by using x/y pad. 

The utility also outputs an audio signal with the level, if you want to get experimental. I recommend disconnecting all it's outputs from the chain otherwise.

## Installation
* Using reapack: Add to ReaPack by importing https://github.com/autotel/jsfx/raw/master/index.xml
* Without reapack: 
    * Locate the JSFX folder on your reaper isntallation (one way to do this is to edit a js text file, 'save as' and instead of saving, copy the url where the current text file is located)
    * Download the text files and locate them on the correct folders.
* Alternatively, you could try using the https://github.com/JoepVanlier/ysfx jsfx host