# Function-Noise-Generator
A basic HTML-based function &amp; noise generator. Generates sine, triangle, square, and saw waveforms at frequencies 1 Hz and higher until limited by the sample rate of the device. 

The noise generator generates white, pink, and Brownian noise. The white noise generator allows users to choose between random (-1 to 1), binary (-1 or 1), and tri-state (-1, 0, or 1) values to simulate a low peak-to-RMS ratio. Pink noise and Brownian noise generators also come with clipping, also to simulate high peak-to-RMS ratios.

Note that this page uses JQuery, so you must download the latest JQuery JavaScript file, rename it as "jquery.min.js", and put it in the same directory as the main file.
