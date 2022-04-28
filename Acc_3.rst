.. Auto generated part

Acc/3  Pressurized Air Warning
------------------------------

**Message info**

============ ===============================
Message      Pressurized Air Warning
Severity     Warning
Display      Error message
Reaction     No stop
Acknowledge  Operator
============ ===============================

.. Information part

**Description**

Warning raised by Air Pressure Monitor in case the compressed air pressure is low.

The air pressure monitor provides two warning inputs, one "normally open" and one "normally closed".
The one that is not linked in the System Manage is ignored (a default value is used). The other one
which is in use should match the sensor output charcteristics. 

**Possible reasons**

- No air pressure
- Sensor defective

**Troubleshooting**

- Check compressed air supply
- Check sensor
- Check System Manager link

