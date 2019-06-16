# sweet15


**View this project writeup at www.chipnetics.com/projects/hw/sweet15/**


The Sweet15 is a retro gamer’s dream, especially for those who are always on the hunt for modern monitors that support 240p, otherwise known as 15khz… or 15.734264Khz if you’re a die-hard fan of gaming! I created it as I was always buying up older monitors, rushing home to hook them up, and then finding out they don’t support 240p. Bummer!

Easily portable and powered by a button cell battery, the Sweet15 allows you to connect to the 15-pin D-Sub connector of any monitor and run various test patterns to ensure the monitor can sync down to 15khz, has no dead/burnt pixels, identify scanline boundaries, and more.

Powered by the ATTINY2313 and a 20Mhz external crystal, the Sweet15 is perfectly suited to run some basic test suites, and is open for further development as the MCU is not soldered in place and can be re-programmed with third party firmware.

Furthermore the Sweet15 has a momentary push button so that you can flip between test patterns readily! There is enough room on the ATTINY2313 to store between 7 or 10 patterns of varying complexity.

As the Sweet15 utilizes digital logic, the color output gamut is the primary colors Red, Green, Blue and its derivatives Yellow, Magenta, Light Blue, White and of course Black. Output has been impedance matched to the industry standard 0.7v at 75 ohms, so what you see for colors will be displayed at the maximum output of the spectrum.
