# ScanIR v2
Impulse Response measurement tool for MATLAB 

### Publications
When using the tool please mention the following publications

Boren, B., & Roginska, A. (2011, October). [Multichannel impulse response measurement in matlab](https://www.researchgate.net/publication/265876631_Multichannel_Impulse_Response_Measurement_in_Matlab). In Audio Engineering Society Convention 131. Audio Engineering Society.

Vanasse, J., Genovese, A. & Roginska, A. (2019, March). Multichannel impulse response measurement in matlab: An update. 

### Description

### Changelog

ScanIR v2.0:
-  Added BRIR option
-  SOFA output file format available
-  Comment section
-  ARDUINO UNO step motor feature integration
-  Default selection of external interface when plugged in at program startup
-  Minor bug fixes

### Installation Requirements 
To run ScanIR you will need the following software
-  MATLAB version 2016a or higher https://www.mathworks.com/
-  Psychtoolbox-3 http://psychtoolbox.org/ 

Optional: 
-  ARDUINO Matlab package https://www.mathworks.com/hardware-support/arduino-matlab.html

### Setup
Once all required components are installed just download the git and open the folder through MATLAB. To run ScanIR, click on the file ScanIR.m and run the script to start the GUI. 

### Hardware required for ARM (Automated Rotating Mount) system
-  [ARDUINO UNO microcontroller](https://store.arduino.cc/arduino-uno-rev3)
-  [ADAFRUIT stepper shield](https://www.adafruit.com/product/1438)
Any compatible step motor of desired resolution should work with the system. The following has been tested in previous works (see other references)
-  [Step motor NEMA23 3A](https://www.omc-stepperonline.com/nema-23-bipolar-18deg-19nm-269ozin-3a-336v-57x57x76mm-4-wires-23hs30-3004s.html)

### Usage 
Please refer to the full user manual pdf for learning the full capabilities and features of the tool.

### See Also
ScanIR v2 has been used for the following studies

Zalles, G., Kamel, Y., Anderson, I., Lee, M. Y., Neil, C., Henry, M., ... & Roginska, A. (2017, October). [A Low-Cost, High-Quality MEMS Ambisonic Microphone](https://s18798.pcdn.co/immersiveaudiogroup/wp-content/uploads/sites/7671/2017/10/Zalles_MEMS.pdf). In Audio Engineering Society Convention 143. Audio Engineering Society.

Genovese, A., Zalles, G., Reardon, G., & Roginska, A. (2018, August). [Acoustic perturbations in HRTFs measured on Mixed Reality Headsets](https://s18798.pcdn.co/immersiveaudiogroup/wp-content/uploads/sites/7671/2018/09/Acoustical_distortions_from_Augment_Reality_devices.pdf). In Audio Engineering Society Conference: 2018 AES International Conference on Audio for Virtual and Augmented Reality. Audio Engineering Society.

