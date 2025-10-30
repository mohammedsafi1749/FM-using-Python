## FM-using-Python

## Aim
To implement and analyze frequency modulation (FM) using Python's NumPy and Matplotlib libraries.

## Apparatus Required

1.Software: Python with NumPy and Matplotlib libraries
2.Hardware: Personal Computer

## Theory

Frequency Modulation (FM) is a method of transmitting information over a carrier wave by varying its frequency in accordance with the amplitude of the input signal (message signal). 

The frequency of the carrier wave is varied according to the instantaneous amplitude of the message signal. The general form of an FM signal is:

## Algorithm

1.Initialize Parameters: Set the values for carrier frequency, message frequency, sampling frequency, and frequency deviation.

2.Generate Time Axis: Create a time vector for the signal duration.

3.Generate Message Signal: Define the message signal as a cosine wave.

4.Compute the Integral of the Message Signal: Calculate the integral of the message signal over time.

5.Generate FM Signal: Apply the FM modulation formula to obtain the modulated signal.

6.Plot the Signals: Use Matplotlib to plot the message signal, carrier signal, and modulated signal.



## Program

    import numpy as np
    import matplotlib.pyplot as plt
    Am = 20.7
    fm = 434
    Ac = 41.4
    fc = 4340
    fs = 43400
    t = np.arange(0, 2/fm, 1/fs)
    m = Am * np.cos(2 * np.pi * fm * t)
    c = Ac * np.cos(2 * np.pi * fc * t)
    b = 5.5
    s = Ac * np.cos((2 * np.pi * fc * t) + b * np.sin(2 * np.pi * fm * t))
    plt.subplot(3,1,1)
    plt.plot(t, m)
    plt.subplot(3,1,2)
    plt.plot(t, c)
    plt.subplot(3,1,3)
    plt.plot(t, s)

## Output Waveform

<img width="554" height="413" alt="image" src="https://github.com/user-attachments/assets/1c510dfa-fe17-456d-af6f-0c7153418533" />

## Tabular Column

![WhatsApp Image 2025-10-15 at 13 10 27_fc19acbf](https://github.com/user-attachments/assets/5167a905-a101-433c-a2a8-b3c5739992d3)

## Result

The message signal, carrier signal, and frequency modulated (FM) signal will be displayed in separate plots. The modulated signal will show frequency variations corresponding to the amplitude of the message signal.
