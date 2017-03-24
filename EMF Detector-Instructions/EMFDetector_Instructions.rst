Solder Solar
============

Design and instructions for a simple DIY solar powered torch.

This kit is designed as a **"Learn to Solder"** kit and as an introduction to **solar power**.

*By: Matthew Little*

*Date: 17th Feb 2017*

*email: hello@curiouselectric.co.uk*

Overview
-------
This is a very simple soldering kit to build a solar powered torch. Use it for camping, exploring, investigating and illuminating.

The unit has a small solar panel which recharges an ultra-capacitor.
There are two LEDs, one white and one red, which are powered by the energy in the ultra-capacitor.

This can be used when out and about, charged during the day and a handy light for night. The white light is useful to find your way around, while the red light will not affect your night vision, so can be used when reading map at night.

The ultra-capacitor is 0.47F which stores enough charge for around 20 minutes of white light, or around 1 hour of red light.

This kit can also be used as a small power supply for other projects (requiring a 3-5.5V power supply). This could be used for very low power monitoring nodes.

Kit Contents
------------

.. image:: Instruction_Photos/components2_sm.jpg?raw=true
   :width: 400px
   
This kit contains the following parts:

+------+-----------------+--------------------------+
| REF  | Description     | Details                  |
+======+=================+==========================+
| C1   | Ultra-Capacitor | 0.47F Electrolytic       |
+------+-----------------+--------------------------+
| D1   | Diode           |                          |
+------+-----------------+--------------------------+
| D2   | LED Red         |                          |
+------+-----------------+--------------------------+
| D3   | LED White       |                          |
+------+-----------------+--------------------------+
| R1   | Resistor        |                          |
+------+-----------------+--------------------------+
| R2   | Resistor        |                          |
+------+-----------------+--------------------------+
| SC1  | Solar PV Panel  |                          |
+------+-----------------+--------------------------+
| SW1  | Switch          |                          |
+------+-----------------+--------------------------+
| SW2  |  Switch         |                          |
+------+-----------------+--------------------------+
| PCB  |  Circuit board  |                          |
+------+-----------------+--------------------------+

This photo shows where each of the components is placed on the PCB.

.. image:: Instruction_Photos/components3_sm.jpg?raw=true
   :width: 400px

Tools Required
--------------
The following tools will be required:

+-----------------+--------------------------+
| Tool            | Description              |
+=================+==========================+
| Soldering Iron  | 25W+ is best             |
+-----------------+--------------------------+
| Solder          | I use lead-free solder   |
+-----------------+--------------------------+
| Side-cutter     | For cutting excess leads |
+-----------------+--------------------------+

.. image:: Instruction_Photos/tools1.png?raw=true
   :width: 400px

A useful guide for learning to solder is available here:

https://cdn.shopify.com/s/files/1/0943/8168/files/soldercomic.pdf

And a more detaileld guide is available here:

https://cdn.shopify.com/s/files/1/0943/8168/files/FullSolderComic_EN.pdf

Step 1: Solder Resistors
------------------------
There are two resistor to solder into the areas marked R1 and R2. These control the current into the LEDs and hence their brightness.

+------+-----------------+--------------------------+
| REF  | Description     | Details                  |
+======+=================+==========================+
| R1   | 330R resistor   | Orange-Orange-Brown-Gold |
+------+-----------------+--------------------------+
| R2   | 120R resistor   | Brown-Red-Black-Gold     |
+------+-----------------+--------------------------+

.. image:: Instruction_Photos/PCB1_sm.jpg?raw=true
   :width: 400px

Step 2: Solder Diode
------------------------

There is one diode to solder into the holes marked D1. This is a 1N5819 Schottky diode, which is suitable for up to 1A and has a low voltage drop.
The diode allow current to pass from the solar cell to the capacitor, but not allow current to flow back to the solar cell.
This diode **must** be inserted with the correct orientation. The white band on the diode must align with the thicker white band on the PCB silk-screen.

.. image:: Instruction_Photos/PCB2_sm.jpg?raw=true
   :width: 400px

Info: The data sheet for the diode is here: https://www.diodes.com/assets/Datasheets/ds23001.pdf

Step 3: Solder Switches
------------------------
There are two switches to solder in locations SW1 and SW2.

.. image:: Instruction_Photos/PCB3_sm.jpg?raw=true
   :width: 400px

Step 4: Solder LEDs
------------------------
There are two LEDs to solder - one white and one red. These look very similar, but the red LED will have a label on it. Do not mix these up when the label taken off.

It is best to solder the white LED first, then take the label off the red LED and solder that.
You must ensure correct polarity of these LEDs.

The positive lead will be the longer lead. The negative lead has a slightly flat side to the LED case. These should align with the markings "+" and "FLAT" on the PCB.

The LEDs are designed to be bent down to align with the PCB into the cut-outs.
Please see photos for clarification.

.. image:: Instruction_Photos/PCB4_sm.jpg?raw=true
   :width: 400px

.. image:: Instruction_Photos/PCB5_sm.jpg?raw=true
   :width: 400px

Step 5: Solder Capacitor
------------------------
The capacitor is a 0.47F ultra-capacitor. This is used to store the energy from the solar cell so it can be used later.
It is an electrolytic capacitor and you **must ensure the correct polarity**.

There are some small white tringles on the capacitor which indicate the negative pin. This pin must align with the large white area of C1 on the PCB silk screen.

Another way to find the pin polarity is that the positive (+) pin is on the bottom of the capacitor and the negative is on the top.
Please see photos for clarification.

.. image:: Instruction_Photos/PCB6_sm.jpg?raw=true
   :width: 400px

.. image:: Instruction_Photos/PCB7_sm.jpg?raw=true
   :width: 400px

Step 6: Solder PV Cell
------------------------
The PV cell is actually a module comprised of a number of small solar PV cells. This unit has a maximum output of 5.5V and a maximum current of 30mA under ideal conditions.

The solar cell is attached to the back of the PCB and so will cover the soldering already done - please **double check** your soldering here and ensure there are not any bad connections or solder short circuits.

We need to align the + connection on the PV cell with the + on the PCB.

We need to add quite a lot of solder to make this conenction. It is best to put a blob of solder on the PV cell pad, then leave it to cool. Then align the PV cell and add more solder until the connection is made to the contacts on the edge of the PCB.

.. image:: Instruction_Photos/PCB8_sm.jpg?raw=true
   :width: 400px

.. image:: Instruction_Photos/PCB9_sm.jpg?raw=true
   :width: 400px
   
.. image:: Instruction_Photos/PCB10_sm.jpg?raw=true
   :width: 400px

Step 7: Attach Key-ring
------------------------
If used, the key-ring can be bent out slightly and fitted into the hole on the side of the PCB.

This is designed to help clip it onto a back-pack etc. We would suggest not using this with keys, as the metal keys might short circuit the components and cause a problem.

.. image:: Instruction_Photos/PCB11_sm.jpg?raw=true
   :width: 400px
   
.. image:: Instruction_Photos/PCB12_sm.jpg?raw=true
   :width: 400px   
   
Step 8: Finished!
------------------------
Place the unit in bright sunlight for a while (at least 10mins).
When pressed, the switches should control each LED.

.. image:: Instruction_Photos/PCB13_sm.jpg?raw=true
   :width: 400px
   
.. image:: Instruction_Photos/InUse1_sm.jpg?raw=true
   :width: 400px

.. image:: Instruction_Photos/InUse2_sm.jpg?raw=true
   :width: 400px
   
.. image:: Instruction_Photos/InUse3_sm.jpg?raw=true
   :width: 400px   

Going Further
----------------------
This unit is also designed to be used as a solar power unit for very low power applications. Connections to P4 are to the terminals of the ultra-capacitor and these can be used to power other projects.
Remember that the voltage can vary from 0V (when totally discharged) up to 5.3V (when totally charged). The attached circuit must be able to withstand this range of voltages.

Troubleshooting
--------------------
This ciruit is relatively simple and designed for the beginner. There are four items which have a polarity and the circuit will not work if any of the following are places the wrong way around:
- Diode
- LEDs
- Capacitor
- PV Cell

Please double check these in case of any issues.

Please also double check the soldering to ensure that there are no short circuits (solder connecting two pads) or 'dry joints' (which do not have enough solder or are not clean).

Circuit Schematic
-------------------
.. image:: Instruction_Photos/Schematic.png?raw=true
   :width: 400px

PCB overview
------------
.. image:: Instruction_Photos/SilkScreen.png?raw=true
   :width: 400px

Suppliers Information
----------------------
We would like you to be happy with this kit. If you are not happy for any reason then please contact us and we will help to sort it out.

Please email **hello@curiouselectric.co.uk** with any questions or comments or please tweet us at **@curiouselectric**

If any parts are missing from your kit then please email **hello@curiouselectric.co.uk** with details and, if possible, where the kit was purchased.

More technical information can be found via **www.curiouselectric.co.uk**

The GITHUB repository for all these files is: **https://github.com/curiouselectric/soldersolar**

This kit has been designed and produced by:

.. image:: Instruction_Photos/CuriousElectricCompany_Logo_Round_Logo_sm.png?raw=true
   :width: 400px


..

   The Curious Electric Company
   
   hello@curiouselectric.co.uk
   
   www.curiouselectric.co.uk
   
   Hopkinson,
   
   21 Station Street,
   
   Nottingham,
   
   NG2 3AJ, UK
