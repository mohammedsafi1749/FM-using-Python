FM-using-Python
Aim

To implement and analyze frequency modulation (FM) using Python's NumPy and Matplotlib libraries.

Apparatus Required

Software: Python with NumPy and Matplotlib libraries
Hardware: Personal Computer
Theory

Frequency Modulation (FM) is a method of transmitting information over a carrier wave by varying its frequency in accordance with the amplitude of the input signal (message signal). The frequency of the carrier wave is varied according to the instantaneous amplitude of the message signal. The general form of an FM signal is:

Algorithm

Initialize Parameters: Set the values for carrier frequency, message frequency, sampling frequency, and frequency deviation.
Generate Time Axis: Create a time vector for the signal duration.
Generate Message Signal: Define the message signal as a cosine wave.
Compute the Integral of the Message Signal: Calculate the integral of the message signal over time.
Generate FM Signal: Apply the FM modulation formula to obtain the modulated signal.
Plot the Signals: Use Matplotlib to plot the message signal, carrier signal, and modulated signal.
Program

Output Waveform

Tabular Column

Calculation

Result

The message signal, carrier signal, and frequency modulated (FM) signal will be displayed in separate plots. The modulated signal will show frequency variations corresponding to the amplitude of the message signal.
