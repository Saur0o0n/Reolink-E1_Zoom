# Reolink-E1_Zoom
Some technical information on Reoling E1 Zoom camera, found inside the device.

I was trying to find serial console - but sadly without luck (I've just looked for it - not measured anything). There is plenty of test points on board - perhaps there is serial somewhere. There is also a possibility, that because of quite a lot of peripherals - there was no free serial pins on SoC anymore.

Camera is "powered" by Novatek NT98515 SoC, with MS41929 stepper motor driver and sensor - all in the head of the camera. In the "foot", there is Qualcomm Atheros AR1021X board connected with USB lines to main board in the head.
