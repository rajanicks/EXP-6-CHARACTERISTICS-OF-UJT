# EXP-6-CHARACTERISTICS-OF-UJT
1. AIM
To plot the characteristics of UJT (2N2446) and to determine the intrinsic stand-off ratio from the graph.
2. APPARATUS REQUIRED
3. LT spice.
4. THEORY
UJT is the Uni Junction Transistor. It is a three-terminal device. The three terminals are emitter, base 1 and base 2. The equivalent circuit consists of two resistors, one variable resistor and one fixed resistor. The ratio of internal resistance is referred to as intrinsic stand-off ratio (η). It is defined as the ratio of the variable resistance to the total resistance.
Due to the existing PN junction, there will be a voltage drop. If voltage is applied to the emitter, the device will not turn on until the input voltage is less than the drop across the diode plus the drop at the variable resistance R1.
When the device is turned on, holes move from emitter to base resulting in a current flow. Due to the sudden increase in charge concentration in the base region, conductivity increases. This causes a drop at base 1. If we further increase the emitter voltage, the device undergoes saturation. Hence UJT has three operating regions: (i) cut-off region, (ii) negative resistance region and (iii) saturation region.
5. Spice Code for UJT Relaxation oscillator
6. <img width="1920" height="1080" alt="AdobeExpressPhotos_c05fa61af71e4c8e8e70b8b7c8202ffc_CopyEdited" src="https://github.com/user-attachments/assets/88964fb0-1498-4c8c-b143-78fd542a5517" />
6. UJT CHARACTERISTIC CURVE
<img width="1920" height="1080" alt="Screenshot 2026-11-27 085244" src="https://github.com/user-attachments/assets/76241cfc-da15-412b-a9b1-4ac2a5a6d62b" />
<img width="1920" height="1080" alt="Screenshot 2026-11-27 091146" src="https://github.com/user-attachments/assets/cf012d1f-e590-423f-ae83-eaa27d6734c2" />


 
Reference model graph from the supplied record.
7. PROCEDURE
1.Download two files and save in same folder 2.Open LT Spice 3.Go to file--->open UJT_oscillator.cir file 4.Run it 5.Output window will open.In output window go to plot settings---->Add trace--->choose v(e) ,click ok.This is input wave form  6.Now close output window,again run the file,in output window go to plot settings--->Add trace--->choose v(b1) ,this is output waveform.Take snap of both input and output wave form

			
			
			
			
			
			
		
11. RESULT
The characteristics of UJT were plotted and the intrinsic stand-off ratio was found.
Intrinsic stand-off ratio, η = 0.56
Peak voltage, VP = 3.3 V
