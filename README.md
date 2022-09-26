# Basic Garage Door Hacking
This is the project demonstrated at the 2022 Arsenal
Lab at Black Hat Las Vegas.

- NOTE: (added by B) - added text of paulgclark's post as appendix to this file

## Overview
After cloning the project, cd into the newly created
garage_door directory, then open gnuradio-companion 
there.

You can then proceed through each project in order until
reaching the final project.

The final project will not be in gnuradio-companion
but will be run in Python from the command line.

Please see Instructions.pdf for more detailed instructions.

For information on installing gnuradio on your computer,
please see www.factorialabs.com

## APPENDIX: paulgclark post from factoralabs.com includes some extra info:

```text
Month: August 2022
Arsenal Labs at Black Hat 2022
Hello Factoria Labs readers! As you may know, Black Hat USA happened earlier this month in Las Vegas. As well as teaching an in-person SDR class, I was also honored to present a hands-on project at the Arsenal Labs – we had a great turnout, as you can see from the picture.

Arsenal Labs
Black Hat 2022 – Arsenal Labs
My project was an end-to-end, RF reversal of a simple garage door protocol. Although the signal produced by the garage door remote was not terribly complicated, the project provided a full view of the reversing process, including:

scanning for the remote’s signal
capturing the signal to disk
tuning and demodulating to produce a digital baseband waveform
identifying the framing and encoding of the baseband waveform and then extracting the bits
building a simple transmitter to implement the reversed protocol
building a more complex transmitter to implement brute force attacks
If you caught my presentation and wanted to look at starter and solution projects, it’s all at:

https://github.com/paulgclark/garage_door

I’ve also included a PDF of the printed handout we had for Arsenal attendees.

If you’re curious, the garage door remote used in the lab was this model:

https://www.amazon.com/dp/B08RSDQKM9

Thanks for reading!
```
