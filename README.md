# Derivatives
In this repository you can find calibration of three models:
  1) Merton's Jump Diffusion, 1976 (MJD). Both for 1 time (Fitting on IV) and for 3 time intervals simultaneously (Fitting on volatility surface)
  2) Heston Model, 1993 (SV). Both for 1 time (Fitting on IV) and for 3 time intervals simultaneously (Fitting on volatility surface)
  3) Bates Model, 1996 (SVJ). Both for 1 time (Fitting on IV) and for 3 time intervals simultaneously (Fitting on volatility surface)

Moreover, here you can find Monte Carlo realization of these models too

There are two files: Fitting on IV.ipynb and Fitting on volatility surface.ipynb. They are quite same but in the Fitting on IV.ipynb I calibrate parameters by implied curve i.e. 1 time period, in the second file I calibrate parameters by volatility surface i.e. on 3 time periods.


As data I used options from Russian exchange - MOEX(https://www.moex.com/ru/derivatives/optionsdesk.aspx?code=Si-6.20&sid=2&sby=1&c4=on&c6=on&c7=on&submit=submit). In the repository this file is named "data.xlsx"



In this project I used a lot http://gouthamanbalaraman.com/blog/quantlib-python-tutorials-with-examples.html and material/books from Yves Hilpisch (Python for finance, Derivatives Analytics with Python: Data Analysis, Models, Simulation, Calibration and Hedging (The Wiley Finance Series)). In this books you can find main ideas and code too.
