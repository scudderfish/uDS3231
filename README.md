# uDS3231
DS3231 for the Wipy

Wire your battery backed DS3231 to the Wipy I2C bus and use it like this :-
```python
MicroPython v1.5-1-ge954604 on 2015-10-21; WiPy with CC3200
Type "help()" for more information.
>>> import time
>>> from DS3231 import DS3231
>>> time.localtime()
(2015, 1, 1, 0, 0, 20, 3, 1)
>>> DS3231().loadTime()
>>> time.localtime()
(2015, 11, 5, 17, 44, 15, 3, 309)
>>> 
```
