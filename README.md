___________________________________________________________________________________________________________________________________________________________________
___________________________________________________________________________________________________________________________________________________________________
___________________________________________________________________________________________________________________________________________________________________
# fourierTransform_Python

___________________________________________________________________________________________________________________________________________________________________
GENERAL DESCRIPTION:
This program applies the Fourier Transform to time-series data containing multiple frequencies. 

___________________________________________________________________________________________________________________________________________________________________
DATA DESCRIPTION:
The data in these scripts are toy lightcurves consisting of simple sine waves with user defined frequencies. The amplitude of these sinusoids are not physically significant, and thus have no real meaning. The duration of the toy lightcurves comes in three types which can also be adjusted in the code.   

___________________________________________________________________________________________________________________________________________________________________
CODE DESCRIPTION: FT.ipynb

The FT.ipynb program is used to compute the fast fourier transform (fft) of a toy signal consisting of 10 user defined frequencies between 30 and 140 Hz.

The lightcurve length is determined by increasing the length of the time array (t, t1, and t2) in accordance with an increase in the number of steps such that the cadence of each simulated lightcurve is identical.

First, the program generates and plots the lightcurves (time vs. amplitude graph) for each time array.

Second, the program will calculate the fft of each lightcurve and plot them normalized.

For example, with the initial input frequencies you should see with the shortest observing run that only the three regimes of pulsation frequencies (~47 Hz, ~87 Hz, and ~127 Hz) were able to be resolved (due to resolution of 1/T ~4 Hz). With the longest observing run, you should see that all 10 frequencies are resolved (due to resolution 1/T2 ~0.1 Hz).

-------------------------------------------------------------------------------------------------------------------------------

CODE DESCRIPTION: FT_animation_HTML.ipynb

The FT_animation_HTML.ipynb animates the increasing resolution of the fft with time.

Both the lightcurve and fft are calculated from 0 to 2.5 seconds.

___________________________________________________________________________________________________________________________________________________________________
RUNNING THE CODE:
This code should be ran in a Jupyter notebook in which the code runs automatically. 


___________________________________________________________________________________________________________________________________________________________________
___________________________________________________________________________________________________________________________________________________________________
___________________________________________________________________________________________________________________________________________________________________
