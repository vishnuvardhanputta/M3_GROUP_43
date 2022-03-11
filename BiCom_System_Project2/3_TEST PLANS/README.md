**TEST PLANS**
===

**HIGH LEVEL TEST PLAN**
--

|Test ID  |Description                        | Input             |Expected Output         |Actual Output          |Pass/Fail |
--------------------                          |---------------    |------------------      |---------------        |----------|--------
|   01    | Print window status               | 1 press button    | Windows status printed | Windows status printed| Pass     |
|   02    | Print alarm status                | 2 press buttons   | Alarm status printed   | Alarm status printed  | Pass     |
|   03    | Print battery info                | 3 press buttons   | Battery info printed   | Battery info printed  | Pass     |
|   04    | Print door status                 | 4 press buttons   | Door status printed    | Door status printed   | Pass     |


**LOW LEVEL TEST PLAN** 
--

|Test ID  |Description                                  | Input            |Expected Output                       |Actual Output                         |Pass/Fail |
--------------------                                    |---------------   |------------------                    |---------------                       |--------- |-
|   01    | All LEDs shall on at same time              | 1 press button   | All LEDs on                          | All LEDs on                          | Pass     |
|   02    | All LEDs shall off at same time             | 2 press buttons  | All LEDs off                         | All LEDs off                         | Pass     |
|   03    | All LEDs shall on in clockwise              | 3 press buttons  | All LEDs on in clockwise manner      | All LEDs on in clockwise manner      | Pass     |
|   04    | All LEDs shall on in anti-clockwise         | 4 press buttons  | All LEDs on in anti-clockwise manner | All LEDs on in anti-clockwise manner | Pass     |
