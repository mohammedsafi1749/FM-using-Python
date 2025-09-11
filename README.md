FM-using-Python
Aim

To implement and analyze frequency modulation (FM) using Python's NumPy and Matplotlib libraries.

Apparatus Required

1.Software: Python with NumPy and Matplotlib libraries

2.Hardware: Personal Computer

Theory

Frequency Modulation (FM) is a method of transmitting information over a carrier wave by varying its frequency in accordance with the amplitude of the input signal (message signal). The frequency of the carrier wave is varied according to the instantaneous amplitude of the message signal. The general form of an FM signal is:

Algorithm

1.Initialize Parameters: Set the values for carrier frequency, message frequency, sampling frequency, and frequency deviation.
2.Generate Time Axis: Create a time vector for the signal duration.
3.Generate Message Signal: Define the message signal as a cosine wave.
4.Compute the Integral of the Message Signal: Calculate the integral of the message signal over time.
5.Generate FM Signal: Apply the FM modulation formula to obtain the modulated signal.
6.Plot the Signals: Use Matplotlib to plot the message signal, carrier signal, and modulated signal.
Program

Output Waveform

<img width="1917" height="1199" alt="Screenshot 2025-09-04 094347" src="https://github.com/user-attachments/assets/0cf372eb-89d5-4fd0-9e0c-2e8ebab65e14" />


Tabular Column

Calculation

Result

The message signal, carrier signal, and frequency modulated (FM) signal will be displayed in separate plots. The modulated signal will show frequency variations corresponding to the amplitude of the message signal.
