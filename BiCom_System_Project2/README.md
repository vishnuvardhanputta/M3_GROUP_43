**BiCom System** 
====================

**INTRODUCTION**
--
A BiCom system is the extension of the unidirectional RKE(Remote Keyless Entry) to bidirectional RKE(Remote Keyless Entry) system. This system is basically use to display the vehicle status/information on the keyfob. The BiCom system can show or display **window status**, **alarm status**, **battery information**, **door status** of the vehicle on the keyfob. There are LEDs to show which feature is currently displaying.

**FEATURES**
--

1) The system can display the window status of the vehicle.
2) The system can display the alarm status of the vehicle.
3) The system can display the battery information of the vehicle..
4) The system can display the door status of the vehicle.

**SWOT ANALYSIS**
![Screenshot (223)](https://user-images.githubusercontent.com/99093515/158006363-dece240f-df3e-47ab-9385-db4d0020bdef.png)

**5W's & 1H**
--

**WHO**

- People who have vehicle. 
 
**WHAT**
 
- It is a system which wirelessly shows status of a vehicle with LED indication.
 
**WHEN**
 
- Whenever the user wants to knows the status of the vehicle 

 **WHERE**
 
 - It can be use anywhere

**WHY**

- To know the status of the vehicle

**HOW**

- The system can be operated by just clicking a button .

**REQUIREMENTS**
--

**HIGH LEVEL REQUIREMENT**

|Test ID  |    Description  |  
----------|-----------------------------------
|HL01     |    The system shall print the window status | 
|HL02     |    The system shall print alarm status      |
|HL03     |    The system shall print vehicle battery information   |
|HL04     |    The system shall print door status  |

**LOW LEVEL REQUIREMENT**

|For High level requirement|Test ID| Description                                                        | 
---------------------------|-------|------------------------------------------------------------------
|HL01                      |LL01   | All the LEDs shall turn on at the same time after single press     |
|HL02                      |LL02   | All the LEDs shall turn off at the same time after two presses     |
|HL03                      |LL03   | All LEDs shall turn on in clockwise manner after three presses     |
|HL04                      |LL04   | All LEDs shall turn on in anti-clockwise manner after four presses |

**ARCHITECTURE**
--
**BEHAVIOURAL DIAGRAM**

![M32_FLOW](https://user-images.githubusercontent.com/98827063/157846591-1c843319-b04e-4a6e-b905-c2135b36a8d0.jpg)


**STRUCTURAL DIAGRAM**

![STRUC](https://user-images.githubusercontent.com/98827063/157846761-82704962-d442-4f84-bd36-716e478a8052.jpg)

**BLOCK DIAGRAM**


![Screenshot (221)](https://user-images.githubusercontent.com/99093515/157855812-73c4b84f-f82b-4321-b728-50bedc4318e2.png)


**CIRCUIT DESIGN**

**TEST PLANS**
---

**HIGH LEVEL TEST PLAN**


|Test ID  |Description                        | Input             |Expected Output         |Actual Output          |Pass/Fail |
--------------------                          |---------------    |------------------      |---------------        |----------|--------
|   01    | Print window status               | 1 press button    | Windows status printed | Windows status printed| Pass     |
|   02    | Print alarm status                | 2 press buttons   | Alarm status printed   | Alarm status printed  | Pass     |
|   03    | Print battery info                | 3 press buttons   | Battery info printed   | Battery info printed  | Pass     |
|   04    | Print door status                 | 4 press buttons   | Door status printed    | Door status printed   | Pass     |


**LOW LEVEL TEST PLAN**


|Test ID  |Description                                  | Input            |Expected Output                       |Actual Output                         |Pass/Fail |
--------------------                                    |---------------   |------------------                    |---------------                       |--------- |-
|   01    | All LEDs shall on at same time              | 1 press button   | All LEDs on                          | All LEDs on                          | Pass     |
|   02    | All LEDs shall off at same time             | 2 press buttons  | All LEDs off                         | All LEDs off                         | Pass     |
|   03    | All LEDs shall on in clockwise              | 3 press buttons  | All LEDs on in clockwise manner      | All LEDs on in clockwise manner      | Pass     |
|   04    | All LEDs shall on in anti-clockwise         | 4 press buttons  | All LEDs on in anti-clockwise manner | All LEDs on in anti-clockwise manner | Pass     |

