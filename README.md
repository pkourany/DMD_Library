DMD_Library
===========

DMD (dot matrix display) library for Spark adapted from Arduino library

Older version of Dot Matrix Library Copyright (C) 2011 Marc Alexander (info@freetronics.com)
Adapted for Spark by Paul Kourany, May 22, 2014

NOTE: Default pin configuration:

DMD		  SPARK
nOE		  A0
A		    D4
B		    D3
CLK		  A3
SCLK	  D2
R_DATA	A5

Spark SPI CS pin A2 is set to HIGH and assumed to by used by another SPI device.  This pin MUST read as HIGH for DMD
to function correctly.
