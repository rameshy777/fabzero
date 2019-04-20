# 3D  Design
## *Scope of work:* 
To design a 3D model for holding the Micromiller bits
The Diameter of the Micromiller bit is 3mm and height is 30mm

## *3D Design Model:*
A small block ( Length: 30mm; Width: 50mm; Height:25mm) containing 5 cylindrical cut of radius 2mm and height 30mm that can properly accommodate 5 Micromiller bits

![bit holder](/images/3d-print-bit-holder.jpeg)
## 3D--Designing Process: Using FreeCad
Open new file in Free cad and draw cube and cylinder as per the given below dimensions:
Cube: l=30mm; w=50mm; height=25mm;
Cylinder1: r=2mm; height=30mm
Placement: x=15; y=5; z=5;
Cylinder2: r=2mm; height=30mm
Placement: x=15; y=15; z=5;
Cylinder3: r=2mm; height=30mm
Placement: x=15; y=25; z=5;
Cylinder4: r=2mm; height=30mm
Placement: x=15; y=35; z=5;
Cylinder5: r=2mm; height=30mm
Placement: x=15; y=45; z=5;

![bit holder 3D design](/images/3ddesign2.jpg)    

Now, apply boolean operation Difference  cut on ->    Cube and cylinder1
apply boolean operation Difference  cut001-> on Cut and cylinder002
apply boolean operation Difference  cut002-> on Cut001 and cylinder003
apply boolean operation Difference  cut003-> on Cut002 and cylinder004
apply boolean operation Difference  cut004-> on Cut003 and cylinder005

Then fusion is applied for proper base with the model. Then for smoother surface  
We  applied Fillet and Chamfer  properties.


# *Output:* #

![bit holder 3D design](/images/3ddesign1.jpg)


The file will be saved in .FCStd format. Export to .stl format.   

Now open the file using 3DXWOX

Save the file with extension .gcode, Export to media drive.

Go to the 3D printer, mount the drive and print.

[Back](/mdfiles/Fab-Lab.md)  ***(Please click  Back to go to Fab-lab)***

