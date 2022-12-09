# monitor_system

As far as I know, Linux does not have a software that can monitor both temperature and cpu clock speed at the same time. 
This repo gathers information using Python psutil and plots the data in a defined time interval.
The script is design to be used as a jupyter notebook like data scientist do.

Engine.ipynb defines the main class that will be used to get data and update the figure.

Run clock_temperature_plot.ipynb to plot.
After running the script, open the url shown (usually http://127.0.0.1:8050).
