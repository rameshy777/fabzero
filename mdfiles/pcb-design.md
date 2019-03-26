#  PCB  Design
The software used for designing the PCB circuit design is KiCad.  
Open KiCad and load new project  
Select schematic layout EeSchema will be open.  
Load the components, Vcc, GND from the place Symbol icon   
Add the required components  From the symbol  Library
Type of components may vary as per the availability at the Lab.    
After selecting the components fix the connections using Place  wire symbol.     
Then, Use **NO Connection** flag for unused pins/connections.   
After completion of circuit, Annotate schematic symbols for un-named components.   
Then, perform electrical rules, and clear all the errors if any.     
Assign PCB footprints to schematic symbols as per the fablab availability and generate net list.  
Run PCBnew to layout pcb. Now schematic circuit convert to PCB layout.
![PCB Design](/images/AssignQ1.png)

PCBnew circuit opened in new window for creating layout. Align the components within the layout.  
Replace connecting white lines by route tracks.  
![PCB Design](/images/AssignA1.jpeg)


Use add graphics line button for drawing the edge cut layer (i.e outer yellow line)   
Then, select the plot format as svg and tick the check box of Exclude pads from silkscreen, negative plot  and zones fills before plotting. Rest of things unchecked.  
Now, 2 nos of .svg format files created and it'll open through inkscape. Select the files and set dpi as 2000 and export as .png format.  
Open the .png files in fabmodules.org and select the .png file in input. In the output format choose .rml format. And in the process, select PCB trace(1/64) for pcb trace and PCB cut(1/32) for cut file.  
Under output, select machine as SRM 20 and fix 0 for X,Y and Z.Remains all default. Now press calculate and save the files as .rml format. Repeat the process for cut file and invert     

 









![PCB Design](/images/Traces-rml.jpeg)



![PCB Design](/images/Cut-Traces-rml.jpg)






