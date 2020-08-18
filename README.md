# Detecting-Open-or-Closed-Space-with-Acoustic-Sensing

<p align="center">
  <img src="Images/spaces.png">
</p>

The purpose of this project is to explore the technical feasility of detecting open/closed space in the indoor environment with acoustic sensing. This results of this project can inform the future design of an indoor item-finding system for lost objects. 

**Hardware Setup** - An android device with an amplified receiver
<p align="center">
  <img src="Images/open_space.png">
</p>
<p align="left" style="color:red">
  The prototype of the SoLr sensor. The left image shows the exterior view of the sensor unit, while the right image shows the interior view of the sensor unit. The numbered components are: (1) speaker (2) microphone (3) processor (4) amplification circuit (5) 9V battery used to power the amplification circuit.
The android device is being used as programmable micro-controller
</p>


**SoLrSpacePropertyDetection** - The Android client responsbile for operating the android device

**SoQrLocServer** - The Java server that sends command to multiple android clients

**AcousticFeaturesExtraction** - The algorithm used for extracting acoustic features and stuff.
