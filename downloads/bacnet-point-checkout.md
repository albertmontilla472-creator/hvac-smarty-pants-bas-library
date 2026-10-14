# HVAC Smarty Pants — BACnet point-checkout worksheet

Use this with a training network or an authorized commissioning task. Begin with discovery and property inspection. A BACnet browser does not replace the vendor application tool.

Project / training setup:
Date / tool:
Controller model / firmware:
BACnet network / device instance:
IP address or routed MS/TP network:
Expected equipment:

## Device identity

| Item | Expected | Observed | Evidence / question |
| --- | --- | --- | --- |
| Device instance | | | |
| Device name | | | |
| Vendor / model | | | |
| Firmware / application version | | | |
| Communication path | | | |

## Point meaning

| Object ID / name | Role | Units | Present value | Status / reliability | Expected range |
| --- | --- | --- | --- | --- | --- |
| | Sensor | | | | |
| | Setpoint | | | | |
| | Command | | | | |
| | Feedback | | | | |

Record whether each point is physical I/O, a calculated value, a network value or a commandable object. If applicable, inspect priority and relinquish-default behavior using the device’s documentation.

## Sequence evidence

| Condition | Expected command | Expected response | Observed values / timestamp | Result |
| --- | --- | --- | --- | --- |
| Normal operating condition | | | | |
| Mode changes | | | | |
| Interlock changes | | | | |
| Failure condition | | | | |
| Override released | | | | |

## Troubleshooting questions

Can the device be discovered?
Can the property be read?
Do value, units and status make sense?
Is the station reading the intended object?
Does the actual equipment match the commanded state?
Which trend or packet evidence would settle the remaining question?

## Closeout

Evidence saved:
Temporary overrides checked and released:
Application/backup reference:
Remaining issue and next action:
