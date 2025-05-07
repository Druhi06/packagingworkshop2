# Packagingworkshop

### 1️⃣ Module 1

<details>
<summary>Click to expand Module description</summary>

# Packaging Evolution: From Basic to 3D Integration

Packaging Course Module 1

Lesson 1
Why is packaging necessary??

![image](https://github.com/user-attachments/assets/9b72ca4f-502e-4e57-91eb-f3d8365be235)

There are two reasons for packaging as mentioned above:
1.	Protecting the devices on the die from corrosion, moisture or any physical damage.
2.	Connecting all the dies on a chip so that they can communicate.

Now as we can see there is an example given of packaging also known as the BGA package:

![image](https://github.com/user-attachments/assets/2c959b28-306d-4dbc-a9c3-86a7a6d9d4c2)
![image](https://github.com/user-attachments/assets/698a1e46-3539-496c-97c1-572a2b227c42)

If we compare it to the die next to it we can see the following:
1.	The black part of the die (right) is a part of the package and is known as the molding compound.
2.	Inside the molding compound we find the die though the placement would vary according to the size of the package.
3.	The die is typically placed on a substrate shown as green in the BGA diagram.
4.	But the die isn’t directly connected to the substrate it is attached using a film or thin layer known as the die attach.
5.	The connections or traces are like stitches with them the substrate can make connections with other dies or parts of the chip.
6.	The wire bonds are the connections from the pad/die to the substrate.
7.	As the bond moves through the traces we see at the bottom a lot of balls lining the surface which will make the connections.
This was just an example of a package but the purpose of showing this is to ensure that people know that the die will be put on a substrate which will have connections.

Basically packaging can be thought as bringing personality to the technically skilled die.

Packaging and Testing Industry

![image](https://github.com/user-attachments/assets/371c98c5-b625-49cf-94ef-7960050a5f06)

Design: The end to end creation of the chip.

Wafer Processing: The design of the chip and die is implemented on the wafer.

Package and Test: This process which we will be learning about has three parts.

a.	Wafer Testing: This is where the die coming from the foundry is tested to see whether it is good or not.
b.	Package: Then if it passes the test it is packaged.
c.	Package Test: Here the package is tested for its readiness.

Assembly: This is where the connections are made to create a system.

Integrated Device Manufacturers or IDM’s are companies that do all the three things shown in the diagram:

![image](https://github.com/user-attachments/assets/863baed6-1a97-432b-ac79-169eb9871ef2)

They design, have a foundry and they have the OSAT which is a facility where they can package and test.

OSAT – Outsourced Semiconductor Assembly and Test

Here outsourced means that the chips come from other companies.

Fabless companies make the design of the chip.

Foundry companies implement the said design on the wafer and make the wafer.

Lesson 2

![image](https://github.com/user-attachments/assets/1180acc6-bc9f-442f-96d7-4ccb8d3ba4c1)

Product Requirement

![image](https://github.com/user-attachments/assets/1b5a2a08-646e-4e21-994a-8baff9d18813)
![image](https://github.com/user-attachments/assets/97af4ef2-fbb0-4e2f-84ac-bd1f6feca93f)

Pin Count

The first thing we need to consider is the pin count as we know that we need to make connections. The speed of the connections is directly connected with the number of connections. Therefore we need to choose accordingly.

Thermal Dissipation

This is another thing we need to consider as we need to make sure that the material we have used under the chip is good. And that the dissipation of the dies is possible.
Eg: High Temp Design (+200 degrees centigrade)

For this design you cannot use substrates such as laminate you would have to use ceramics. Therefore the substrate choice is very important during thermal dissipation.

Form Factor

This decides the area of the package on the board. Like if you want to miniaturise a board then the form factor would help you fit the package in the allotted area.

Reliability and Durability

This is directly affected by the material used to make the package as all packages are made with different materials.

Cost 

This is a very important factor in any technology where it is important to minimise the cost in every possible way without reducing the quality.

Typical Package Structure

![image](https://github.com/user-attachments/assets/ebc90464-02e1-4f23-b23b-d7b926d95179)

The die sits on the carrier which could be a substrate or multiple layers. Then we need to make the connections between the carrier and the die. These are the first modality or interlayer connection known as the die-to carrier connections. The second modality or the interlayer connection is the Carrier to Board interconnection. On top of all this we put the molding compound which we saw as the black layer.

![image](https://github.com/user-attachments/assets/00d951c9-3866-4f93-bf94-a526e9a98a65)

These are some packages divided by structure:

1.	DIP – Dual Inline Packages. They are called this as we see the pins coming out of the package from the 2 sides.  The pins are mounted through holes. If the pins are only coming from one side they are called Single Inline Packages or SIP’s.

2.	Transistor Outline – TO. They are for MOSFETs.

3.	PGA – Pin Grid Array. They have pins mounted just like the DIPs but the pins are smaller and they form an array like in the BGA packages that we saw earlier. You also cover a larger area.

These are all through-hole mounting packages where you need holes to mount pins.

1.	QFN – Quad Flat No Lead. You don’t see lead and it is a flat package.

2.	QFP – Quad Flat Pin. You see the pins and lead but the pins are soldered on instead of connecting with holes.

3.	PBGA – Plastic Ball Grid Array. This is the same as the BGA package. We can see that the circles/ balls have been embossed.

4.	LGA – Len Grid Array. The balls on this are not embossed.

5.	CSP – Chip Scale Package. This package looks very similar to the BGA package but one difference is that this CSP is almost the size of the chip hence the name. This is made because of layout constraint as the board has a set area for the package.  

Lesson 3

6.	MCM -  Multi Chip Module. Here there are multiple dies in one package. An example of this is the Intel Broadwell

7.	PoP – Packages on Package where there is a package on the same kind of package like a BGA on a BGA.

8.	CoWoS is a very advanced packaging. An example is the Nvidia H100 board.

Now we can think of the materials for the carrier and there are multiple options for this.

![image](https://github.com/user-attachments/assets/9dc2d46b-cdc7-41f1-9db9-88747db34658)

Leadframe is when the die is put on metal which is the case for the DIPs and the QFNs.
Laminate which is the plastic package and it consists of many layers.
Ceramic which is the perfect carrier for high temperature requirements.
Other options are the organic RDLs, silicon and glass.

The options for the interconnections are:

1.	Wire Bond – Stitching from the pad on the die to the package substrate. An example would be the flyover.

2.	Bump/Solder – They are connected without holes. And they are underneath. An example is the subway.
 Anatomy of Packages. 

![image](https://github.com/user-attachments/assets/ce258fb6-b861-474c-95bf-2a60d42851e9)

The DIP package is shown here with 12 pins and the die is the yellow block with the wire bonds the flyover lines connected to the 12 pins. Then finally we have the molding compound shown in grey. 

The QFN package is shown here with the die attached to a leadframe using die attach but there is no lead coming out of the package. The connections are made with the wire bonds. The connections are on all four sides and there are also thermal pads visible. Now if we just make the leadframe smaller then it can become the size of the chip and work as the CSP. 

The leadframe can be sized as we want it. Finally the Quad Flat Pin is connected to a leadframe but it also has lead coming out of it as pins.

![image](https://github.com/user-attachments/assets/87f0ba50-d8fb-49cc-99f8-18513ac5adfa)
![image](https://github.com/user-attachments/assets/175fd8f0-8343-4769-a929-4007afba14af)

The difference between the two chips shown here is that in the wire bond PBGA we are connecting using the wire bonds and in the Flip Chip PBGA we flip the chip so that the connections already made on the chip can be used to make connections with other packages.
The FC – CSP or the Flip Chip CSP is very similar to the Flip Chip PBGA but the only difference is that the package size is almost as big as the die itself.

![image](https://github.com/user-attachments/assets/6d8f5883-10b9-46b4-b37d-2dbdd27b1d38)

2D: This shows the simplest multi-chip module where the dies are simply connected to the substrate. But there is a problem that if we want to connect both the dies we have to go through the whole substrate to do that.

2.1D: Now to remove the problem of the long connections between the dies we add an RDL or a redistribution layer. This allows us to make internal connections without going through the whole substrate.

Lesson 4

2.3D: Replacing the RDL with an organic interposer. The role of the interposer is to help the connections fan out the multitude of connections. The basic idea is that as the connections increase there are multiple layers needed to help fan those out.

2.5D: Replacing the organic interposer with a silicon interposer to make the connections work faster. It is called 2.5D as the dies are still not on top of each another like 3D. AN example of this is the CoWoS chip (Chip on Wafer on Substrate)

Note: The distance between the bumps is called the bump pitch.

Summary Diagram

![image](https://github.com/user-attachments/assets/c6eb06f0-c838-4e6f-9aed-1f43e9146c41)

For the 3D packaging we typically see the Flip Chip technology where multiple dies are placed on top of each other and connect through the bumps making a subway. An example is shown below.

Lesson 5

Comparison 

DIP

Pros: 
1.	Low cost
2.	Easy to assemble
3.	Durable
Cons:
1.	Less pins
2.	Big Package size
3.	Incompatibility with automated assembly
Common Applications
1.	Consumer electronics
2.	Industrial applications
3.	Legacy systems

QFN

Pros:
1.	Compact 
2.	Good thermal performance
3.	Lightweight
Cons:
1.	Hard to test pins
2.	Not easily access pins
3.	Less reparability
4.	Less input/output pins than the QFP
Common Applications
1.	Smartphone
2.	Tablet
3.	Automotive telecommunications

QFP

Pros:
1.	Higher pin density
2.	Easy to inspect
3.	Easy to solder
Cons:
1.	Pins are easily damaged
2.	Pins difficult to repair
Common Applications:
1.	Micro-controllers
2.	Micro-processors
3.	ASICs


PBGA
Pros:
1.	High Pin Count
2.	Good electrical performance
3.	Good thermal performance
Cons:
1.	Difficult to inspect
2.	Difficult to rework
3.	Limited shelf life
4.	Costlier than QFN
Common Applications
1.	High performance ICs
CSP
Pros: 
1.	Small size
2.	Higher electrical performance at low cost
Cons:
1.	Limited I/O pins
2.	Reliability issues
Common Applications
1.	Smartphones
2.	IoT
3.	Wearable devices
2.1D
Pros:
1.	Higher level of integration
2.	Better performance
3.	Power efficiency

Cons:
1.	Longer die to die connections
Common Applications
1.	Data centre chips
2.	RF wireless modules
3.	Space avionics
2.3D
Pros:
1.	Higher density of I/O pins
2.	Routing at lower cost
Cons:
1.	Reliability issues in polymer RDL
2.	Lower I/O density than 2.5D
Common Applications
1.	High performance computing segments
2.5D
Pros:
1.	High I/O throughput
2.	Heterogenous integration
3.	Lower latency
Cons:
1.	Costlier than 2.1D
2.	Reliability concerns
Common Applications
1.	Data centre GPU for AI 

Steps after product requirements

Now we will see how to design the package we have chosen. We will do this by talking about the package manufacturing, testing and then designing. This will help us by making it easier to understand the failures and success’ in packaging.

</details>

---
