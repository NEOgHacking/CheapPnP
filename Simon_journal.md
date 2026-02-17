# Feb 16 - 4h
Today we had a joint call to figure out what we wanted to do and who will do what. We began with discussing if this whole idea was even possible after a few arguments we came to the conclusion we could probably compleet a part of the PnP in time for blueprint to have sponsering. We made a list of what needed to happen and what are the things that need to be done first and what are the things that could be done after blueprint that wouldn't hurt that much in the wallet. We came to the global idea that the frame with the motion system was the most important part to be done. Here is the list we made for what needs to be done first and what can wait.
1. main frame
2. motion
3. head
4. camera
5. mounting plate
6. feeders
7. vacuum
This is the main list of things we will be doing and in what order. Software will be done by tty7 mostly in between. I will do most of the hardware part of the build.

### Requirements
First lets make a list of what we want this thing to be capable of.
1. Min. 200x200 PCB size possibility.
2. Sizes down to at least 0402 and 0.5mm pitch ic's.
3. At least feeders from 2 sides, but hopefully 3/4 sides.
4. Ridgid frame with 0.2mm accuracy.
5. Nozzle swap mechanism.
6. TODO

### Complecations
A PnP is not cheap. Than we have the even more difficult part, we will do a split project and we both want one. For this reason this will be a tier 1 project but it will still be difficult. $200 for a frame and motion is really little for the stuff we wanted. But tty7 had a good idea, you can get linear rails from jlcmc for really cheap. $13 each and we only need 3. Than aluminum extrusion is really cheap. Stepper motors will also be pretty cheap except the one for the extruder that is a nema8 with a hollow shaft to allow air to flow thru. The control for the printer will be my custom 3D printer mainboard, it has 5 stepper outputs and plenty of io left over for extra functions needed for a PnP. It will be a very tight fit to make everything fit in the $200 budget.


### Begin design
We started an shared onshape document to begin the design, tty7 began with the frame and i began with replicating the stepper with the connections. after a while i got here.
![NEMA8 with nozzle holder and air connection](assets/NEMA8 with nozzle holder and air connection.png)
