.. Auto generated part

Acc/2  Lubrication Pressure Warning
-----------------------------------

**Message info**

============ ===============================
Message      Lubrication Pressure Warning
Severity     Warning
Display      Error message
Reaction     No stop
Acknowledge  Operator
============ ===============================

.. Information part

**Description**

Error raised on Grease lubrication systems in case the grease pressure has not build up
in time.

**Possible reasons**

- Hardware input sMapIn.greasePressureOk not linked
- Grease reservoir empty
- Hardware defective 

**Troubleshooting**

- Check device
- Check wiring
- Check if device is powered on
- Check System Manager link
- The delay time for builing up the grease pressure is a configuration parameter. Check for correct values
  and possibly increase the delay time

