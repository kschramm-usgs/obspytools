<<<<<<< HEAD
obspytools
========

These are various tools at ASL that use obspy and python


Contents
========
eqinfo is a simple replacement for the old FORTRAN eq_info

randcal is a first cut at a random calibration routine

pdfs is a simple ultility to make pdfs

readmetadata is a program for reading pieces of metadata

dataconvert has various programs for converting data types

selfnoise is a program for calculating self-noise using the Sleeman method

estgain  is a program to compare the gain of two sensors in the mid-band
=======
eqinfopy
========

Earthquake info using webservices to get quick information about events


Usage
========

The following usage is allowed:
eqinfo.py -h
usage: eqinfo.py [-h] [-n NUMBER] -t TIME [-v] [-mM MINMAG] [-MM MAXMAG]
                 [-md MINDEP]

Code to get earthquake info

optional arguments:
  -h, --help            show this help message and exit
  -n NUMBER, --number NUMBER
                        Number of days to search
  -t TIME, --time TIME  Start time to search from: YYYY,DDD
  -v, --verbose         Run in verbose (debug) mode
  -mM MINMAG, --minMag MINMAG
                        Minimum magnitude
  -MM MAXMAG, --MaxMag MAXMAG
                        Minimum magnitude
  -md MINDEP, --mindep MINDEP
                        Minimum depth (km)


Output
========

The output is in rows with the year, day of year, hour, minute, second,
latitude, longitude, depth, and magnitude
>>>>>>> b234118d0c2e5f6312b9e5b561b629ac0147c88c


To Do
========
<<<<<<< HEAD

Setup a common response library between the programs

Document better

Include the stepcal correlation code

Merge with synthetics code





=======
We need to add different event types beyond earthquakes.

We also need to add various possible outputs.

This could potentially be used for finding arrival times also.
>>>>>>> b234118d0c2e5f6312b9e5b561b629ac0147c88c
