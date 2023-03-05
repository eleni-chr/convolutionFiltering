# convolutionFiltering
Convolution filtering functions using a Gaussian filter or a bandpass filter.

Functions written by Eleni Christoforidou in MATLAB R2022b.

GaussianFilter: This function takes as input a [1xN] vector x, which represents a signal, and a scalar sigma. It convolves x with a Gaussian with standard deviation sigma. The function outputs the resulting signal y.

BandPassFilter: This function takes as input a [1 x N] vector x (the signal), a scalar Fs (the sampling frequency of the signal), a [1 x 2] vector freq_range (the low and high cut-off frequencies for the bandpass of the filter), and an integer W (the window size of the filter). The function creates the filter and applies it to create the output filtered signal y.
