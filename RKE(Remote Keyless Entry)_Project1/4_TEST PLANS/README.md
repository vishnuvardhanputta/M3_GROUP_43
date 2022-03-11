**HIGH LEVEL TEST PLAN**
======

|Test ID  |Description                        | Input             |Expected Output         |Actual Output          |Pass/Fail |
--------------------                          |---------------    |------------------      |---------------        |----------|-----------
|   01    | Vehicle door lock                 | 1 press button    | Vehicle locked         | Vehicle locked        | Pass     |
|   02    | Vehicle door unlock               | 2 press buttons   | Vehicle unlocked       | Vehicle unlocked      | Pass     |
|   03    | Alarm activation/deactivation     | 3 press buttons   | Activated/deactivated  | Activated/deactivated | Pass     |
|   04    | Approach light                    | 4 press buttons   | On                     | On                    | Pass     |


**LOW LEVEL TEST PLAN** 
====

|Test ID  |Description                                  | Input            |Expected Output                       |Actual Output                         |Pass/Fail |
--------------------                                    |---------------   |------------------                    |---------------                       |--------- |-
|   01    | All LEDs shall on at same time              | 1 press button   | All LEDs on                          | All LEDs on                          | Pass     |
|   02    | All LEDs shall off at same time             | 2 press buttons  | All LEDs off                         | All LEDs off                         | Pass     |
|   03    | All LEDs shall on in clockwise              | 3 press buttons  | All LEDs on in clockwise manner      | All LEDs on in clockwise manner      | Pass     |
|   04    | All LEDs shall on in anti-clockwise         | 4 press buttons  | All LEDs on in anti-clockwise manner | All LEDs on in anti-clockwise manner | Pass     |
