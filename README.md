# Condition-monitoring-of-hydraulic-systems-Data-Set
url: https://archive.ics.uci.edu/ml/datasets/Condition+monitoring+of+hydraulic+systems


DataSet Information
The data set was experimentally obtained with a hydraulic test rig. This test rig consists of a primary working and a secondary cooling-filtration circuit which are connected via the oil tank [1], [2]. The system cyclically repeats constant load cycles (duration 60 seconds) and measures process values such as pressures, volume flows and temperatures while the condition of four hydraulic components (cooler, valve, pump and accumulator) is quantitatively varied.

Attribute Information:
The data set contains raw process sensor data (i.e. without feature extraction) which are structured as matrices (tab-delimited) with the rows representing the cycles and the columns the data points within a cycle. The sensors involved are: Sensor Physical quantity Unit Sampling rate PS1 Pressure bar 100 Hz PS2 Pressure bar 100 Hz PS3 Pressure bar 100 Hz PS4 Pressure bar 100 Hz PS5 Pressure bar 100 Hz PS6 Pressure bar 100 Hz EPS1 Motor power W 100 Hz FS1 Volume flow l/min 10 Hz FS2 Volume flow l/min 10 Hz TS1 Temperature Â°C 1 Hz TS2 Temperature Â°C 1 Hz TS3 Temperature Â°C 1 Hz TS4 Temperature Â°C 1 Hz VS1 Vibration mm/s 1 Hz CE Cooling efficiency (virtual) % 1 Hz CP Cooling power (virtual) kW 1 Hz SE Efficiency factor % 1 Hz

The target condition values are cycle-wise annotated in â€˜profile.txtâ€˜ (tab-delimited). As before, the row number represents the cycle number. The columns are

1: Cooler condition / %: 3: close to total failure 20: reduced effifiency 100: full efficiency

2: Valve condition / %: 100: optimal switching behavior 90: small lag 80: severe lag 73: close to total failure

3: Internal pump leakage: 0: no leakage 1: weak leakage 2: severe leakage

4: Hydraulic accumulator / bar: 130: optimal pressure 115: slightly reduced pressure 100: severely reduced pressure 90: close to total failure

5: stable flag: 0: conditions were stable 1: static conditions might not have been reached yet

Relevant Papers:
[1] Nikolai Helwig, Eliseo Pignanelli, Andreas SchÃ¼tze, â€˜Condition Monitoring of a Complex Hydraulic System Using Multivariate Statisticsâ€™, in Proc. I2MTC-2015 - 2015 IEEE International Instrumentation and Measurement Technology Conference, paper PPS1-39, Pisa, Italy, May 11-14, 2015, doi: 10.1109/I2MTC.2015.7151267. [2] N. Helwig, A. SchÃ¼tze, â€˜Detecting and compensating sensor faults in a hydraulic condition monitoring systemâ€™, in Proc. SENSOR 2015 - 17th International Conference on Sensors and Measurement Technology, oral presentation D8.1, Nuremberg, Germany, May 19-21, 2015, doi: 10.5162/sensor2015/D8.1. [3] Tizian Schneider, Nikolai Helwig, Andreas SchÃ¼tze, â€˜Automatic feature extraction and selection for classification of cyclical time series dataâ€™, tm - Technisches Messen (2017), 84(3), 198â€“206, doi: 10.1515/teme-2016-0072.
