# Detecting-Open-or-Closed-Space-with-Acoustic-Sensing

[insert a picture in here]

The purpose of this project is to explore the technical feasility of detecting open/closed space in the indoor environment with acoustic sensing. This results of this project can inform the future design of an indoor item-finding system for lost objects. 

**Hardware Setup** - An android device with amplied receiver
<p align="center">
  <img src="Images/open_space.png" width="300" height="500">
</p>
The android device is being used as programmable micro-controller

**SoLrSpacePropertyDetection** - The Android client responsbile for operating the android device

**SoQrLocServer** - The Java server that sends command to multiple android clients

**AcousticFeaturesExtraction** - The algorithm used for extracting acoustic features and stuff.
