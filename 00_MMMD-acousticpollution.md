# Making Media Making Devices
## Acoustic Pollution analysis with Raspberry Pi

---

Since I've moved to New York I've noticed the amount of acoustic pollution happening. I live in a neighborhood where cars with motor-noise-enhancers and loud urban music is a common thing. Also buses, trucks, motorbikes pass by making a rather loud noise, at any time of the day. So I wonder if I'm just being a bit to sensitive or the actual decibels of the street noise is a considerable value. For this I connected a USB microphone to the Pi and checked online for reference on how to use it. 

The first step was making sure that the device is being recognized by the sound card. Then I found this piece of [code](https://makersportal.com/blog/2018/8/23/recording-audio-on-the-raspberry-pi-with-python-and-a-usb-microphone) that uses `pyaudio` and `wave` libraries to make a .wav file. To get a closer look at the recorded file, I downloaded Audacity, a very simple digital audio workspace that did more that I expected. I was planning on writing some code to set a threshold and find peaks in the recording. But Audacity comes with this feature built-in good enough for this prototype and to learn the procedure of this type of analysis. 

<img src="https://github.com/karihigh/s3_code-of-music/blob/master/20190923_204250.jpg?raw=true" style="width: 100%; text-align: center;"/>

Below there is a screen recording of the raspberry workflow (click on the image to open Youtube video).

[<img src="https://github.com/karihigh/s3_code-of-music/blob/master/video.png?raw=true">](https://www.youtube.com/embed/K-j6QG2TgNU)

For this experiment I recorded the sound of the ITP Floor. On a second iteration I would like to run the raspberry in a battery and run the code in the fire escape of my appartment an entire night. 

<img src="https://github.com/karihigh/s3_code-of-music/blob/master/audioanalysis.png?raw=true" style="width: 100%; text-align: center;"/>