# Packagingworkshop

### 1️⃣ Module 2

<details>
<summary>Click to expand Module description</summary>

Word Documents Available

# From Wafer To Package: Assembly And Manufacturing Essentials

Lesson 1

Package Manufacturing

Review of Supply Chain

1.	First, we have the design house which have the building blocks (EDA Tools, foundry PDKs) to make the design of the chip. After designing we perform the IC design test program (GDSII).

2.	Then we have wafer fabrication where the IC design is fabricated on the wafer. The necessities are silicon wafers, manufacturing equipment, gases, chemicals, other materials.

3.	The next step is packaging, assembly and testing where individual ICs are assembled in a package and tested. For this we need the different substrates (leadframe, laminate, ceramic etc), tools, materials, chemicals, lids.

4.	Now we have the board assembly and test where many packages are assembled on boards and tested. For this we need PCBs, tools, and materials.

5.	Finally, we have product assembly and test where the final product is manufactured using component tools.

![image](https://github.com/user-attachments/assets/1ef64faf-6942-461d-9196-33491a097b97)
	
Here we are focused on the third part of the supply chain package assembly and testing. The input for this is the wafer with the fabricated IC.

Introduction of a Package Manufacturing Unit.

ATMP – Assembly, Testing, Marking and Packaging

OSAT – Outsourced Semiconductor Assembly and Test

ATMP is a process driven unit.

The ATMP unit can be in-house or it can be OSAT where the chip design is sent to an OSAT unit and they make the chip.

Clean room area is either measured by classes or grades and for the class the lower the number the number is the higher the cost of the unit and in grades the higher the grade is the higher the cost of building the unit is.

![image](https://github.com/user-attachments/assets/2cf34b9a-96d9-4d2a-887d-d0d6dd5dbb14)	

The clean room takes usually takes 50 – 70% of the space in the unit.

The testing area takes 20 – 30% of the space in the unit.

The utility and maintenance room is very necessary and makes sure the unit runs properly.

The material preparation and storage room holds all the materials needed for the different packaging processes.

Finally the warehouse is there to store the chips before shipping.

Lesson 2

Activities inside the cleanroom area

First, we have the incoming wafer carrier which holds the wafers.

When the wafers arrive they only have the chips on the front side and the back is just the supporting substrate and that substrate makes the wafer very thick. So before processing we need to make the wafer as thin as possible. 

1.	Wafer inspection – to check whether the wafer is of good quality, not damaged and processible.

2.	After that is checked we have wafer front tape lamination to protect the processing on the front of the wafer.

3.	Then we have the wafer backside grinding. For this process the wafer and flipped and put on a chuck table which is rotated at high speeds while a mechanical force is applied. This force erodes the excess silicon.

Note: If this process is not done properly then the wafer will break as it is subjected to a lot of stress.

1.	Now we tape frame the backside of the wafer. This mechanically supports the wafer.

2.	Now we will dice the wafer as we know there are many dies on the wafer. This is a 2-step process unless you go with the blade directly. But direct blade slicing has a lot of cons. Therefore we first use laser grooving to create marks/ grooves for the blade to follow.

Link for video:
https://drive.google.com/file/d/1RNSt-A62O7AdWDILbVOuuXaSkpyjOa-1/view?usp=sharing

Lesson 3

Three Types of Packaging

•	Wire Bond Packaging

In this we have a substrate and then a die on top with connections using a wire.
a.	First by looking at the wafer map we will choose a good die and out it on the substrate.
i.	Dispense the epoxy where you want the chip to be.
ii.	Pick the chip
iii.	Place on the Die Attach Film (DAF)

Video: https://drive.google.com/file/d/1lQt5tAbdytzSCV7Ls-7ih0lsNYACvA3Z/view?usp=sharing

•	Then we need to do the process of curing (heating) to give it mechanical strength.

•	First using the dispenser we create a free air ball.

•	You can use temperature, pressure or vibration to attach the ball to the die and make a bond.

•	The dispenser moves up and makes a loop before reaching the pad’s surface.

•	Then we make a crescent bond which is cutting of the excess wire using force and we are left with a wire tail.

•	Finally reheat the wire tail to make a free air ball and begin the process again.

Video: https://drive.google.com/file/d/1eW2A9F1qK5IBJgx6QgzEml_viaRvwKIO/view?usp=sharing

•	Using the transfer method we now pass the molding compound on the chip.

•	Then the marking of the packages happens through lasers and this helps to identify the package.

•	Then we have the process of singulation where we bring back the blade and dice the package. 

Lesson 4

2.	Flip Chip Packaging 

![image](https://github.com/user-attachments/assets/be6fa348-43dd-4f68-af4d-9754bacb7896)

•	First, we apply under ball metallisation which creates a base.

•	Then apply a metal in a pattern.

•	Finally, apply the solder and pattern again.

•	After that we apply the process of reflow where the solder goes through a high temperature furnace and becomes a bump on the backside 
of the chip and there are many such bumps.

•	Then you flip the die with the solder balls.

Now we need to place the die on the substrate but before we can do that we need to create a surface where the balls can connect with the substrate.

•	So first we create pads on the substrate’s surface and apply Flux. Flux is an environment used to protect the dies.

•	After making the pads we can use two things to join the substrate and die.

  o	We have to use heating and compression.

•	Here we have used thermocompression to join/solder the balls to the pads.

•	Then we spray the chip with a solvent to remove the flux as we no longer need it since the connections have been made.

•	Then we dispense underfill to make connections between the die and substrate.

•	After that we cure the underfill by heating the chip.

•	Finally, we add the molding compound.

The process through which the flip chip is bonded to the substrate is called the Mass Reflow and Thermo-Compression Process.

•	Then we mark the chip which will help in identification later.

Now we need to create bumps on the substrate so that the chip can connect with the outer world.

•	For that first we flip the package.

•	Then we do the ball mounting in its regular fashion.

•	Finally we put the package through reflow and get our final result.

Lesson 5

2.	Fan-out Wafer Level Package

The one difference between the flip chip package and the wafer level package is that the chip is connected to the solder balls through the RDL.

•	First, we will pick and place the known good dies on a temporary carrier.

•	Then we will add the molding compound to protect the chip.

•	After that we will remove the temporary carrier to get a reconstituted wafer (chips on molding compound).

Now we need to prepare the RDL for that we will use coating of dielectric material and metal.

•	First, we make a metal layer.

•	Then add the dielectric layer and create grooves.

•	After that we add another metal layer and pattern it. The pattern will be made by covering the grooves and making more.

Now you have to continue these steps until you have the desired number of layers. In this case we have three layers.

![image](https://github.com/user-attachments/assets/1ed62326-e474-47e7-add2-38b697eb3dd9)

•	We now put the prepared RDL on the reconstituted wafers.

•	Then we attach the solder balls.

•	After that we mark the wafer.

•	Finally through the process of singulation we separate the individual chips.

If you have high pin count and low pitch then fan-out chip are the best for you.

Processing video
https://drive.google.com/file/d/19Zxx-L-sjkz3ZFuM0WUFlRX46RfqTvaM/view?usp=sharing

</details>

---
