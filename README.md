# HRsense
HRsense is graphical user interface implemented via Matlab App Designer that allows to remotely record, process, visualize, and store data from a photoplethysmograph (PPG). Data may be retrieved from 3 sources:
- the computer's local drive
- the bluetooth channel
-  USB interfaces

The main procedure of HRsense uses cumulative averaging to chart the evolution of heart rate over time, and the Fast Fourier Transform (FFT) is used to obtain the spectrum of the raw data recorded by the sensor.

# HOW TO RUN
Running this application is quite straightforward. Prior, you should install the signal processing software MATLAB on your computer. In addition, to collect data from the Bluetooth channel and USB interfaces, a MATLAB add-on toolbox should be installed. This component is named 'Instrument Control Toolbox'. 
Then, all the files available in this repertory should be downloaded and placed in the same folder. The last step consists of double-clicking the file 'HRsense.mlapp' and the graphical user interface will come up on the Matlab environment. A sample data file named 'data.mat' is provided to test the import fonctionality.

# AUTHORS
- MASSALA MBOYI Gilles Yowel*
- NGOUNGOUROU Térence Wilvain
- NVE HOUNKPONOU Orphée
- Marius MASSALA
- Pierre MOUKELI MBINDZOUKOU
- Jung-Hoon Han

*Correspondence to: gilles.massala@stu.jejunu.ac.kr

Version 1.0, March 2023.
