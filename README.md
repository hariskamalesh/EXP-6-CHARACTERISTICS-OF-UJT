# EXP-6-CHARACTERISTICS-OF-UJT
1. AIM
To plot the characteristics of UJT (2N2446) and to determine the intrinsic stand-off ratio from the graph.

2. Software Required
3. LT spice

THEORY
UJT is the Uni Junction Transistor. It is a three-terminal device. The three terminals are emitter, base 1 and base 2. The equivalent circuit consists of two resistors, one variable resistor and one fixed resistor. The ratio of internal resistance is referred to as intrinsic stand-off ratio (η). It is defined as the ratio of the variable resistance to the total resistance.
Due to the existing PN junction, there will be a voltage drop. If voltage is applied to the emitter, the device will not turn on until the input voltage is less than the drop across the diode plus the drop at the variable resistance R1.
When the device is turned on, holes move from emitter to base resulting in a current flow. Due to the sudden increase in charge concentration in the base region, conductivity increases. This causes a drop at base 1. If we further increase the emitter voltage, the device undergoes saturation. Hence UJT has three operating regions: (i) cut-off region, (ii) negative resistance region and (iii) saturation region.

Spice Code for UJT Relaxation Oscillator
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0d090734-d635-4256-ae98-6134b544474e" />

 
Reference circuit diagram reproduced from the supplied record.

UJT CHARACTERISTIC CURVE
<img width="1920" height="1080" alt="Screenshot (92)" src="https://github.com/user-attachments/assets/b9939281-1c3b-4581-b00f-2b36bc646dcc" />
<img width="1920" height="1080" alt="Screenshot (91)" src="https://github.com/user-attachments/assets/196cac47-123f-409c-9f39-9c249ff3f6d5" />

The emitter characteristic is plotted between emitter voltage VE and emitter current IE. The curve contains the cut-off region, peak point, negative resistance region, valley point and saturation region.
 
Reference model graph from the supplied record.

PROCEDURE
1.Download two files and save in same folder 2.Open LT Spice 3.Go to file--->open UJT_oscillator.cir file 4.Run it 5.Output window will open.In output window go to plot settings---->Add trace--->choose v(e) ,click ok.This is input wave form  6.Now close output window,again run the file,in output window go to plot settings--->Add trace--->choose v(b1) ,this is output waveform.Take snap of both input and output wave form

RESULT
The characteristics of UJT were plotted and the intrinsic stand-off ratio was found.
Intrinsic stand-off ratio, η = 0.56
Peak voltage, VP = 3.3 V
