# Detecting-Open-or-Closed-Space-with-Acoustic-Sensing

<p align="center">
  <img src="Images/spaces.png">
</p>

The purpose of this project is to explore the technical feasility of detecting open/closed space in the indoor environment with acoustic sensing. For the evaluation, We identifed 21 spaces, commonly seen in office or household environments and placed a self-made prototype in each space. The prototype is capable of emitting and receiving acoustic waves. Since open and closed spaces would produce different reflections of waves, we can train a machine classifier to learn the differences and differentiate the two spaces. The results of this project could inform future design of an <b>indoor item-finding system for lost objects<b>. 

**Hardware Setup** - An android device with an amplified receiver
<p align="center">
  <img src="Images/open_space.png">
</p>
<p align="left" style="color:red">
  
  The prototype is made of: (1) speaker (2) microphone (3) android device (4) amplification circuit (5) 9V battery used to power the amplification circuit.
The android device is being used as programmable micro-controller
</p>


**SoLrSpacePropertyDetection** - The Android client responsbile for operating the android device

**SoQrLocServer** - The Java server that sends command to multiple android clients. Timing.

**AcousticFeaturesExtraction** - The algorithm used for extracting acoustic features and stuff. 10-fold cross-validation
