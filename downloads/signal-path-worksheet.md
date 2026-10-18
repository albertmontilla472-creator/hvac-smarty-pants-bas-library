# The Controls Exchange — signal-path and sequence worksheet

Use one sheet for one piece of equipment. Start on paper; add tool screenshots and trend evidence when a lab is available.

Equipment / sequence:
Date:
Controller model / protocol / firmware:
Engineering tool / release:
Lesson / timestamp:

## 1. Write the sequence

What starts operation?
What must be true before the output enables?
What makes it stop?
What is the expected response?
What failure needs an alarm?

## 2. Trace the signal

| Step | Point or component | Meaning / units | Input → output | Where it runs |
| --- | --- | --- | --- | --- |
| Occupancy | | | | |
| Enable conditions | | | | |
| Control demand | | | | |
| Command | | | | |
| Measured response | | | | |
| Fault detection | | | | |

Separate physical sensors, network values, internal logic, commands and feedback. Identify which interlocks belong in the controller and which actions occur in Niagara.

## 3. Predict before testing

| Test condition | Expected command | Expected feedback | Alarm / timing | Evidence / result |
| --- | --- | --- | --- | --- |
| Normal start | | | | |
| Unoccupied | | | | |
| Safety condition changes | | | | |
| Failed proof | | | | |
| Sensor unavailable | | | | |
| Manual override / release | | | | |

## 4. Choose evidence

Which command and response will you trend?
Which units and sample intervals matter?
How will you tell a logic problem from a communication or mechanical problem?

## 5. Explain what you learned

My prediction:
What the demonstration or test actually showed:
One correction to my sequence:
Next question:
