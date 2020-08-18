# Detecting-Open-or-Closed-Space-with-Acoustic-Sensing

<p align="center">
  <img src="Images/spaces.png">
</p>

The purpose of this project is to explore the technical feasilities of detecting open/closed space in the indoor environment with acoustic sensing. For the evaluation, We identifed 21 spaces, commonly seen in office or household environments and placed a self-made prototype in each space. The prototype is capable of emitting and receiving acoustic waves. Since open and closed spaces would produce different reflections of waves, we can train a machine classifier to learn the differences and differentiate the two spaces. The results of this project could inform future design of an <b>indoor item-finding system for lost objects</b>. 

**Hardware Setup - An Android device with an amplified receiver**
<p align="center">
  <img src="Images/open_space.png">
</p>


The prototype is made of: (1) speaker (2) microphone (3) android device (4) amplification circuit (5) 9V battery used to power the <a href="http://afrotechmods.com/tutorials/2017/01/17/how-to-make-a-simple-1-watt-audio-amplifier-lm386-based/">amplification circuit</a>.
The android device is essentially being used as programmable micro-controller. We added an extenal speaker-microphone module to the device for two primary reasons: (1) To amplify the acoustic signal. (2) To place the microphone and the speaker on the same side so the body of the phone won't impede the propagation of sound waves. 

**SoQrLocServer - The Java server** 
The SoQrLocServer is a Java server that runs on PC. 

**SoLrSpacePropertyDetection - The TCP client responsbile for operating the android device**
<p align="center">
  <img src="Images/client2.JPG">
</p>
SoLrSpacePropertyDetection is the TCP (Transmission Control Protocol) client that runs on the Android device. It's responsible for collecting and sending the acoustic data throught the WLAN to the Javs server. To run the client, install the client app on a smartphone through Android Studio and connect the smartphone to the WLAN. 



**AcousticFeaturesExtraction** - The algorithm used for extracting acoustic features and stuff. 10-fold cross-validation
