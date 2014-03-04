img-fft
=======

This program is a tiny tool for fourier transform on image processing. It is implemented by the powerful language, Python, which provides the awesome mathematical libraries like numpy, matplotlib. The program let you generate the results of the fourier transform of the image quickly.

How to use
======

Command line:  
    
    $ python img-fft.py lena.png
    
Some detail:    

The default is output both figure image and the data file.
    
    Usage: python img-fft.py [options] [(filename|directory)+]
    
    Options:
      -f, --figure  Only output the Fourier transform figure file
      -d, --data    Only output the Fourier transform data file

Results
======

lena.bmp & fft-lena.bmp

<img src="lena.bmp" height="200" />
<img src="fft-lena.bmp" height="200" />

fft-data-lena.matrix

    6.107,7.665,6.888,7.622,7.225,6.984,6.787, ... ,6.231
    6.318,5.881,5.533,6.911,7.208,7.215,7.084, ... ,6.398
    6.713,7.500,7.346,6.683,6.811,7.561,7.001, ... ,4.442
    7.163,6.742,7.424,7.458,5.834,6.784,7.289, ... ,6.246
    6.784,7.228,7.300,6.807,6.110,6.841,4.407, ... ,5.527
                        :
                        :
                        :
                        :
                        :
    6.528,6.978,6.652,7.033,7.053,6.760,7.116, ... ,6.967
    
