# Marlin-Ender-3-Pro-Config
Marlin Ender 3 Pro Config версия 2.0.6 bugfix
1. https://www.youtube.com/watch?v=VlIFgICFWbM
2. https://ender3.club/%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0_3D_Touch
3. https://ender3.club/%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0_SKR_1.3_%2B_TMC2208_UART
4. https://www.danbp.org/p/en/node/142
5. https://www.danbp.org/p/en/node/143
6. https://marlinfw.org/
![Схема](https://github.com/XroMSPb/Marlin-Ender-3-Pro-Config/blob/master/bltouch.JPG?raw=true)

https://www.thingiverse.com/thing:4441537
You must make these changes in your firmware. Sending the commands via Pronterface or OctoPrint works too.
BMG E-steps (need to calibrate later): 415 steps/mm
Probe offsets for RH BMG's: X = +45.8, Y = +14.2 ¹
Probe offsets for LH BMG's (not tested): X = +37.5, Y = +14.2 ¹
If your prints are off-centered, you may have to use these home offsets: X = -4.55, Y = -15.60. ²
Marlin commands (RH):

M92 E415
M851 X45.8 Y14.2
M206 X-4.55 Y-15.60
M500
