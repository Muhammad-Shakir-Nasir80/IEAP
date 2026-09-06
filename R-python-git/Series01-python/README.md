# IEAP - Series01 Python Assignment

This is my assignment for Series 01 of the IEAP Python course.
The goal was to load a raw ECG signal, convert it into real units, and plot it.

## What I did

- Imported numpy, pandas and matplotlib
- Loaded the raw ECG data from data/DATA.CSV using numpy.genfromtxt
- Converted the raw values into millivolts using the A/D converter gain (1024 µV/unit)
- Built a time axis in seconds using the sampling frequency (1000 Hz)
- Made a simple plot with all 3 leads together
- Made a second, better plot with one subplot per lead, like a real ECG monitor

## Files

- SERIES01.ipynb - the notebook with all the code
- data/ - the raw ECG data file
- LICENSE - license for this project

## What I learned

This assignment helped me practice reading raw data, doing unit conversions,
and making cleaner plots using subplots in matplotlib.
