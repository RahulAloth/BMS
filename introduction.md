This repository covers following learning objectives.
Learn how to describe the key components of a battery system
Understand the role of the BMS in monitoring and conrolling battery performance
Learn to identify the importance of thermal mangement and safety measures.

We have already learned how a single lithium ion cell works. However battery poacks are installed in electric vehicles. This raise the wquestions:
What is the difference ?
How do we get from a battery cvell to a battery pack and what else makes up the battery pack. 

Many of us have seen reports and pictures of electric vehicles on fire. Once out of safe operating range there is no stopping the thermal runaay of a battery. The result is firest that continue to cause difficulties even for firefighters.
Howerver preenceting such hazardous situations i only one task of the battery management system and thermal management system.
What else is omitored and controlled byeond that?
How can the health of a battery for example be measured and its service life inffluenced in addition to compliance with operating limits ?
# Battery System:
Having already introduced you to the world of batteries, lets focus on the battery system and take a closer look at the thermal and battery management system in particulat in the following vidieo. 

Dr, Ing . Dipl. Wirt Ing. Heiner Heimes. RWTH Aachen university

Differnt systems based on Lithoioum ion technomoplgsy.
We need battery management system and thermal management system this ensure the battery running.

What are the main car components in battery management systems ?
- Battery cells.
-   Smallest element and key elements of the battery system.
-   Ebergy< storage of the whole system.
-   One cell is not enough. So we need to integrate all of these battery into one big battery Module. 
-  Lot of different cells in the battery to ensure the battery works. One battery module, not possbiele to drive a car. So we do the same trick to integrate into Batery pack.
-  Battery module then becomes battery pack.
  So Battery Cell -> Battery Module -> Battery Pack.I want to do the deepdrive into these component,

Battery Cells:
Different kinds of battery cells. Same structure, same active materials but different in shapes.
- Prismatic battery cells.( Higher cost)
- Cylindrical sells. ( winding inside it, its round cell) It make sure that it has a good cooling system. Outer arias of battery should have same temperature everywhere.
- Pauch cell, having a battery and an aluminoium foil around the battery cells. Its flexible in shapoe. Pauch cells are differnt cutting tools for the electrods, disadvantage is low mechanicla robustness.

- Interem conclusion is that depends oin the application , which one car manufacturing want to use.

  # Battery modules.

  Putting different cells in housing and puit cooling controllers on it.
  So the scalability is increased with modulabirits. With this, we can go one step further to integrate into Battery Pack.

  Integrate 8- 10 module in one battery packe. In the battery systems there are some other comonpionets likle Thermal management system, battery management system ..
  Enclosure or cover make sure there is no dirt, and no water inside the battery, it will create a short cut. Thermal runaway, risk of fire.
  So make sure tightness of battery

  # Bus bars
  
  # Fuse Box :
  Simple componet, its a classical bypart, make sure expenseive components are protected from Furges. So use high quality.

  # Service disconnect
  Service disconnect is an important components.
  # Thermal mangement system and Battery managment system.
  Make sure its the brain. Every data is collected and then its doing calculation and make sure that battery is working in the right operating window.
  Thermal managment system consists of cooling medium and different cooling etc.

  We do deepdive into BMS and TMC.

  # Thermal Managment systeem.
  # Battery management system.
  BS, Li Ion works not without a brain.(BMS). It make sure that each single compoinent works in the right operating window and collect the data. So from where it gets the data=?
  It should have a Temperature sensor and a voltage sensor of each cells.
  BM slave collects all data from sensor and send them into BMS. Each Single battery has Temperature sensor and Voltage sensor.
  BM Slave is placed with each battery module and all has one Battery Management Master.
  BMS is work with Temperate and voltage.
  Thermal management system consists of cooliing plate, cooling medium and all. this has  an operating window and make sure that battery does not leave from this window.
  Draw Grapgh of VCell voltage vs Temperature wchi produces an operating area.
  BMS and TMC make sure every component is working inside this windo.w

# Focus on key tasks of this Battery Management system and its tasks at a glance.

  - BMS first step is to do measurement. 
  - Calculate SOC( State of Charge ) 100% means fully charge example.
  - Its an important information for the car driver.
  - BMS also responsible for SOH( State of Heal ) It represents the value of quality of the battery. During the lifetime, Heals goes down. If its below 80 % may be we need to replace the battery.

# Thermal Management system
- BMS need help from Thermal management system,
- Base Plate
     Its a genious tech. You are only placveing on the bottom of the battery system. So its a less effort assembly , by part is cheap. Only small area of the battery is in contact so it leads to a point where is cooling capacity is not so high. Example : BMW
- Hose cooling
    Rooting hose directly through the battery system. Its so flexible, but dissadvantage is flexible part have to assemble manually, assembly effort is higher. It has the higher cooling efficiteny. Example Tesla
- Cooling plate
  Cooling plate cna direclty place beteen the battery. It has maximum cooling power, Cooling plate is expensoive, assembly is higher cost. Example Opel Ampera E
- Liquid cooling
- There is a high effort to handle liquid directly into the liquid compoents this technoilogy has high efficieny, cooling liquid surface contact is higher. Mitsubishi iMiEV as example.
Which is the best depends on the application.

We come to a poiont of Hazarodus situation.
So to make sure that correct themal and batteryx management, there is a risk of thermal runnaway. WE have to imaginge its a chain reaction. Its the temperatire of the battery and enery released short period of time. 400 Degree or higher its so aboslute critical to fire.. 

Reasons for thermal runnaway.
Internal short cut. 
If seperator has a whole between anode and cathode and if its contact then this happens.
External shortcut.
Due to accident, difformation can happen and short cut can happen.
If BMS is not working like overcharging There can be faulure in senosrsm then can occur overcharging and thermal runnaway and finally fire. 

Each LiOn battery should have good BMS and Thermal Managfement System. Its the critical part and 
Summary
Differnt componets of battery
Different cell type,
Battery module and Batteradadjlakdsj a
Keep in mind that each lithium-ion battery system requires a good thermal and battery management system. You should not try to cut out any costs at these two components because this would be very critical in case of hazardous situations.


Battery Cells : Storage systems for electric vehicles are largely based on lithium-ion battery cells.
Battery module : The battery cells are mounted and interconnected in the battery modules.
Battery Pack : This is followed by the assembly of the battery pack and peripheral system components.

Battery cell
Cylindrical cell shapes:

ADVANTAGE: are produced with high throughput in round winding technology
DISADVANTAGE: comparatively inefficient cooling of the cells
Prismatic cell shapes: 

ADVANTAGE: are also manufactured with high throughput; due to the larger surface area, heat dissipation from prismatic cells occurs more easily than from the cylindrical type
DISADVANTAGE: more manufacturing steps are required than with cylindrical cells
Pouch cell shape (coffee-bag, flat cell): the main difference to the prismatic cell shape is the cover used (aluminum foil pocket laminated with plastic)

ADVANTAGE: reduced mass of the housing and thus lower heat capacity
DISADVANTAGE: lower mechanical robustness

Battery module
Depending on the required battery capacity, several battery cells are connected in series and parallel to form a battery module.
Block structure: all individual storage elements are assembled into a single block with an electrical collector structure, sensors and other components and placed in a battery housing.
The advantage of the modular design is the easier handling of the components during assembly and possible maintenance of the entire system (interchangeability) as well as the scalability of the system.

Battery pack
The battery pack consists of any number of individual battery modules, which are interconnected with each other.
In addition to the battery modules, other system components are included, which enable safe operation.

The entire battery system for electric vehicles consists of the following components (click on the i-buttons to learn more):

Busbars
Electrically connect the battery modules and connect the modules to the contactors.
Battery Management System (BMS)
The BMS ensures safe operating temperatures and voltages of the cells. It measures the remaining charge of the pack and the state of health (SoH). It ensures that the battery is correctly connected and isolated before the contactors are closed.
Service Disconnect
Used to electrically disconnect the battery from the vehicle during service/ maintenance.
Battery Modules:
Modules are designed and integrated according to cell format and vehicle requirements.
Enclosure
The structural enclosure protects the battery from damage and provides protection against external influences and the ingress of dirt. It also protects service employees  from high voltage components.
Fuse Box
Fuses protect expensive components from damage due to surges and faults. Contactors electrically disconnect the battery pack from the vehicle.
Thermal management connection
Mostly peripheral temperature control of a suitable medium to operate the battery in the optimum temperature window.
Thermal management connection
Mostly peripheral temperature control of a suitable medium to operate the battery in the optimum temperature window.
Enclosure
The structural enclosure protects the battery from damage and provides protection against external influences and the ingress of dirt. It also protects service employees  from high voltage components.





  

  
  
  
  
  
  
  



-  
