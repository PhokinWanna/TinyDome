# TinyDome_Prototype
[Mock-Up]

**Start's Date:** 29/7/25


**Goal's or Finish's Date:** 29/1/26


**Author:** Phokin Wanna (Maybe have another Member,in future!)

**Property:** Have all function that Ballistic Missile Defense System could had. But, this prototype was no harm and just an experiment.

**Description:**For The IOT project ONLY,That have potential to integrate into Mobile SAM Prototype.
**This project has a propose just to learn about IOT and sensor learning,
 DO NOT have any determination or propose to create an object to harm anybody in physically and pyschology.
 Vice Versa, If this project was process to success, it will help another people that might not know or 
didn't have any acknowlage about Engineer and Military to understand, how the Defensive Missile System WORK!**


**Raod Map:**

1.List every object and every Resource or everything that have to use it in project (I mean EVERYTHING).

2.Begin to write the Work's diagram(mean The way or how to doing it) to show how the system work, connected of Hardware and Software (NO NEED to get in detail, just use a basic word).

3.Find the way to get the gadget,tools, and equipment (Just the way how to find it and then get it ALL). 

4.Then, think about how to start a Project, In STEP BY STEP (Like flowchart or Stepchart).

5.When Finish the flowchart, Have to doing belong the plan to PART BY PART (don't have to doing it in all at once). But, doing it in part. And then later, combine  each part together to make it into ONE PART (Like a jigsaw)
 or Product (Prototype).

6.Put everthing that was Fully successed into 1 PRODUCT (Prototype).

7.Put the prototype to test system, If find any pproblem (Sure! it have to had a problrm and even it was a tiny probelm), Have to record it in note or another subject and then find the way to solve that problem.

8.After the problem or the mistake has been SOLVED, Redo at MARK 7, Again, And Again and Again. Untill the product was successfully complete.
(Optional) 9.If the product was doing well and can integrate, PREPARE TO MAKE ANOTHER PROJECT FOR IT. If don't, PREPARE FOR MAINTAINACE PART.


**Budget:** Around 2,000 - 5,000 baht.


**List of Main Tools & Equipments**(Didn't include circuit part)**:**

Q = Quantity(Piece), P=Price(Baht)[*May change, up to date of purchase*], N = Note

1.ESP32-WROOM-32; Q=1, P=0, N="Necessary"

2.Breadboard-Mini-Size; Q=1-2(up to scale), P=60, N="Necessary"

3.Ultrasonic-Sensor-HC-SRO4; Q=1, P=30, N="Necessary"

4.Jumper-Line-(Male-to-Female); Q=10-15(up to scale), P=30, N="Necessary"

5.Servo-Motor-MG-995; Q=2-4(up to scale), P=120, N="Necessary"

6.Spring-Luncher/Selenoid; Q=1, P=300-400, N="Necessary"

7.18650-Battery; Q=4-6, P=100-300, N="Necessary"

8.Battery-Holder; Q=1, P=30, N="Necessary"

9.Green&Red-LED; Q=2, P=15, N="Necessary"

10.Buzzer-Passive-Module-Low-Level-Trigger; Q=1, P=12-15, N="Necessary"

11.USB-Cam/Pi-Cam; Q=1, P=300, N="Necessary"

12.Joystick-HW-504; Q=1, P=0, N="Optional" 

13.PMS-3003-PM2.5-Air-Quality-Sensor-SNP-00146; Q=1, P=0, N="Optional"


**Basic Diagram:**

Note<The "Top viwe side" was in draw.io on repo>

*Classify By Function:*

1.Input-Module='A'

2.Processing-Module='B'

3.Tracking-Module='C'

4.Fire-Mechanism='D'

5.Output-Module='E'

6.Communication/Interface='F'

7.Energy-Resource='G'


*Classify By Hardware:*

1.Ultrasonic-Sensor=['A']

2.Mainboard-ESP32=['B','F']

3.Selenoid=['C','D']

4.USB-Cam=['A']

5.LED=['E']

6.Buzzer=['E']

7.Energy-Resource=['G']


*Module's Relationship:*

Note<Full Scale and more detail in Draw.io>





	[Tracking-Module] *------------* [Fire-Mechanism]
	*		|			A
	|	A	|			|
	|	|	|			|
	|	|	|-------|------> [Output-Module]
	|	|	V	|
	|			|	 				    MQTT   
	| [Processing-Module]----------> [Communication/Interface-Module] {------} [Server/Cloud] 
	|			
	|	|	A   A	
	|	|	|   |----------- [Energy-Resource-Module]
	|	|	|
	|	V	|	
	*		|
	[Input-Module]--|





**Expectation:** Hopefully that, This project can make a prototype that show or explain about how Iron-dome or 
ballistic missile defence system(BSDM) work! To make another people understand, how dose and How many Function
that have to include in the system to predict the moving object in air and Importantly could resistant the
suspect object that coming into radar area.


**Summarize**(date-by-date)**:**

1/8/25: Today, I finish all of it! and now, prepare to commit and push all of it(This file) to my git-repo. Next, prepare to proceesing the first Module. 
