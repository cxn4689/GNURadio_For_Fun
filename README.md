# GNURadio_For_Fun
Learn how to play with GNURadio for fun

1. demod_tcp_qt.grc can work with xrit decoder (https://github.com/opensatelliteproject/xritdemod) through TCP link.  You can also connect xrti-rx (https://github.com/sam210723/xrit-rx) to generate image through goestools flow (use the hacked file in this repo).  This is for offline use with baseband wav file of GK-2A

2. demod_tcp_qt_QPSK.grc is used offline to demod 72K sybmpol of Meter MN2 from baseband wav file. Generated .s file can be used by LRPT Decoder to generate image

3. AM_DEMOD.grc is used to demodulate AM signal from baseband wav file. This for air traffic audio.

Baseband wav file rate can be found in parameters 'file_rate' in eac .grc file.
