# ErrorAndAnomalyDetection

## VL53L0X

* 25 degree cone of detection.  ( 25 degrees across, not 25 degress from center :-( )
The VL53L0X has 5 different ranging modes.  For our purposes, it seems that only the LongDistance mode is useful.


In LongDistance mode the VL53L0X:
* Takes a measurement every 33 ms
* Returns an integer from 0 to 2000, indicating millimeters of distance to the reflecting object (hereinafter, the object)
* Returns 8190 when it doesn't sense an object

However, a multitude of conditions can cause inaccurate or erroneous readings.
* Unknown error - often it will make a series of good measurements and without any environmental changes simply fails to read one or more times (returning 8190) then starts returning good measurements again.
* Dog moves his head in front of the sensor... (not actually erroneous, but an anomaly that needs to be ignored)
* closest obstacle leaves the detection cone temporarily
* A butterfly flaps its wings in Brazil

Solution:

?????
