# Matlab-Spoken-Letter-Analyzer
A Matlab program which, once the library is filled with your samples, recognizes the letter you have said, using Fourier transformation and spectrograms.
This projects originates from the Course "Applications in Matlab and Octave" at BFH.

## Functionality
The program reads in an audio signal from the user. It then computes the Fourer transformation of this singal using Matlab's built-in fft() function. This transformation allows us to create a spectrogram, which has the time and the frequency on its axis and the amplitude as a colour for each pixel.
Once the library of a few letters is created, the program compares lets the user compare its letter to the ones in the library. This comparison of the spectrograms is done using the SSIM (Structural Similarity) index which is a built-in Matlab function. Other indices such as PSNR or the MSE are computed but not used. This could be a future feature, which increases the predicive accuracy of the program.

## Usage
Read the report or follow the Matlab live scripts, to use the program.

