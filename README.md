# temporal_segmentation_gestural_control

![rearranger_ball_DEMO_14_APR_2023.mp4](https://gitlab.jyu.fi/juigmend/temporal_segmentation_gestural_control/-/raw/main/more_documentation/rearranger_ball_DEMO_14_APR_2023.mp4)

![Poster](https://gitlab.jyu.fi/juigmend/temporal_segmentation_gestural_control/-/raw/main/more_documentation/delayed_control_unsupervised_segmentation_POSTER.png)

More information:

https://gitlab.jyu.fi/juigmend/temporal_segmentation_gestural_control/-/blob/main/Mendoza_NIME_2023.pdf

## Instructions:

https://gitlab.jyu.fi/juigmend/temporal_segmentation_gestural_control/-/blob/main/GESTURAL_AUDIO_REARRANGER_instructions.txt

## Dependencies:

https://puredata.info/downloads/pd-extended/releases/0.42.5

http://www.wekinator.org/

##  To get the Myo running in Mac Operating System:

The Myo might work with other operating systems but its manufacturer ceased support years ago so only the solution for Mac OS is documented here. Anyway, the sensor can be replaced easily (e.g., with other controller like a joystick, video tracking, etc.) by modifying the Pure Data patch [GESTURAL_AUDIO_REARRANGER](https://gitlab.jyu.fi/juigmend/temporal_segmentation_gestural_control/-/blob/main/GESTURAL_AUDIO_REARRANGER_WORK.pd).

To get data from a Myo armband the Myo Connect software should be installed and the myo.framework file should be copied into ~/Library/Frameworks. If the Frameworks folder doesn’t exist you need to create it. Then the DaemonMYO script should be executed, just by double clicking on it.
Download DaemonMYO from here:

https://github.com/federicoVisi/KineToolbox/blob/master/input+ML/DaemonMYO

Download the Myo framework from here:

https://github.com/samyk/myo-osc
https://github.com/benkuper/MyOSC

If the Myo stops working (red blinking light), try copying in it the firmware file (myo-firmware-1.5.1970.hex) when connected with the USB cable.




