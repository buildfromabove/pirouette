# Mechanical Overview
This file gives an overview of the mechanical design of the PiRouette, with relevant links

## Update October 27, 2021
It's been a while since I've updated this page, so here goes. I've revised the OML and the button / thumbstick layouts based on a test print of the controller OML that I did shortly after the last update. The figure below shows what the current OML looks like:

![CADFig2](https://user-images.githubusercontent.com/80743890/139198908-5172ad8b-2777-4524-b17e-6e636e8b2371.png)
<p align= "center">
  <b> Figure 10.27.21.a </b> The second iteration of the controller and main chassis OML's.
</p>

I've also added in buttons to the assembly; the buttons are in roughly the locations that they will be in when I have the controller PCB in the CAD. I've decided that I'm going to use the 8mm soft tactile buttons from Adafruit (https://www.adafruit.com/product/3101), since I would prefer a more squishy button feel (I'm weird, I know) to the snappy feel that you get from traditional buttons.

The controllers are more slim now, with the handle parts tucked closer to the edge. The layout has also changed to be a bit more conventional. I did this because it was hard to reach the interior buttons with my thumbs with the old layout.

## Update August 3, 2021
Figure 1 below shows the first iteration of the controller and main body. As of right now, the CAD exists as two hollow shells; one each for the controller and the main chassis. I have not yet blocked off the requisite space for ports, circuit boards, or and wires, etc.

![image](https://user-images.githubusercontent.com/80743890/128109751-90f00847-a155-41af-a9b5-3639fd79b4be.png)
<p align="center"> 
  <b>Figure 1.</b> The first iteration of the controller and main chassis OML's. 
</p>

At this point, I am mainly interested in the ergonomics of the controller; as that will probably be the first large hurdle to jump over. I test printed the controller OML over the weekend, and discovered that the controller is wider than I had thought. Additionally, the buttons are too far from the edge of the controller for a comfortable grip. Last, the bump on the rear side of the controller is too shallow; it is uncomfortable to grip when it is that shallow.

Below is the first iteration of the controller OML. The controller CAD is physically split in two to facilitate 3D-printing. There is an alignment part that sticks into the main body of the PiRouette (the upside-down 'U'-shaped part). I also have the buttons around the hole that the joystick will go into. I noticed that it will be hard to press the left and down buttons when the joystick is installed, so I will adjust their layout to be easier to press in the next iteration.

![image](https://user-images.githubusercontent.com/80743890/128109795-622c8012-641b-483d-b71b-77804ff2b584.png)
<p align="center">
  <b> Figure 2. </b> The first iteration of the controller OML.
</p>

![image](https://user-images.githubusercontent.com/80743890/128110449-74f518da-cb39-408a-954d-e34f3cee6c3a.png)
<p align="center"
   <b> Figure 3. </b> The underside of the controller (first iteration)
</p>
