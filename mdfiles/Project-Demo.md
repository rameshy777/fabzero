

#  Project   Presentation
   
![Project Slide](/images/projectslide.png)




### Aim of the Project:  
The main aim of the project is to develop an iBELL, intelligent BELL. 
Intelligence means "to fool others". If A fools B, then A is intelligent than B.   It is not always true that "All intelligent are not fools".
Also, it is  not  true  that " All fools  are not intelligent". 

In  our day today life, we  always try  to play  an intelligent  role.  But  still sometimes once a while we may be fooled by others. We can act intelligently  on  those  which we see, or on  those that happen in front of us.  But, it is challenging to play an intelligent role over the events that happens behind us. 

So, this thought has  motivated us to develop an intelligent system called "iBELL" which helps us to be intelligent  even behind our eye  sight. 

### Procedure/Description:  
iBELL  is an Intelligent BELL. It is a normal electronic BELL programed to behave intelligent role.
Whenever anybody misuses or  tries to fool, it goes to "freezing mode"  and gets  activated after specified time.
ie, If you press the buzzer and hold for more time,  immediately without causing nuisance to the owner.  It automatically goes  to "Freeze Mode". Also,  if anybody repeatedly presses the buzzer  it enters to "Freeze Mode". Like this,  several cases of events  are worked out  and  programed to behave  intelligently.

### Hardware Requirement / Electronic Components  used:    
Resistors---500 ohm --2nos.  
Resistors---10 ohm  --2nos.  
LED---------2nos.. Green, Blue  
Micro Controller--ATtiny 44  --1 no.  
Capacitor--------1Micro Farad --1no.  
Switch Button--1no.  
ISP header-----1no.  
Speaker/Buzzer---------1no.  
Resistor--50ohm--2nos.  
Mosfet----------1no. 


### Software Requirement:  
Markdown,  Git, KiCad,  Visual Studio Code,  Freecad,  Inscape,  gimp,  Cura,  3DWOX,  Arduino,   AVR  Code

### PCB Design: 

The  Circuit design, Schematic  diagram  and cutting  is done  using the micromiller.  

#### PCB  board after soldering:    
![PCB Board](/images/pcb-board-ATtiny44.png) 

#### iBELL Circuit Design:    
![Project Slide](/images/iBell-circuit-diag.jpg)   
#### iBELL Schematic Diagram:     
![Project Slide](/images/iBell-schematic-layout.jpg) 
#### Buzzer Circuit 3d-Design:        
![Project Slide](/images/buzzer-schema-3d.png) 
#### Buzzer Trace:        
![Project Slide](/images/buzzer_trace.png)

### Implementation:  

Now, the components are soldered as  per the PCB  design  on  the  circuit board.
We have arrived  at  two  circuit boards, one  is  the micro controller circuit,  the  other  is the  MOSFET  connected  to the  speaker.  We have also used additional 2 nos.of 50ohm  resistors connected in parallel to suppress the  generated heat. Oscilloscope  was used to check the  working functionality of the speaker.     

### Coding:  
AVR  program  was written as per our  requirement. Through the programmer, using Arduino, we have compiled and successfully loaded the AVR code in to the micro controller to work intelligently as  per  our requirements.
#### AVR Code:        
![iBELL AVR CODE ](/images/avr-code-last.png)


### Testing:    
Moulding: 3d designed  case, 3d printing,   heating glue gun,     Vinyl  sticker. 

### Final Output/Result:   


### Future Enhancement:  







![Project video](/images/project-video.mp4)
#### Click [Back](/mdfiles/pcb-design.md)
#### Click [Fablab-Menu](/mdfiles/Fab-Lab.md)
#### Click [Next](/mdfiles/Thankyou.md)