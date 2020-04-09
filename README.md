# ArduinoFrequencyMeasurement
 High sampling rate (38.5KHz) frequency and amplitude analysis on Arduino

##Use
 Analog Pin A0 - DC Biased Audio input (must be within arduino's 0-5V range, check [this](http://interface.khm.de/index.php/lab/interfaces-advanced/arduino-realtime-audio-processing/index.html) link for info)

##What does it do?
This code returns the current measured frequency (in Hz) and amplitude (0-100) using the Arduino's built in ADC running in 8-bit measurement mode. 

It's used in another of my projects, the room lights project, to make lights in my room change color based on the audio signal provided to it.