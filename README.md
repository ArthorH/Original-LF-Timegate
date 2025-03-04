![da](https://github.com/user-attachments/assets/72f89c5f-3965-4c38-af1a-255bf9265079)
## Project Status: **Finished**  
**Design** ✅ — **Fabrication** ✅ — **Assembly** ✅ — **Bringup** ✅ — **Testing** ✅  
## Key technologies:
<img align="center" height="70" src="https://github.com/user-attachments/assets/b9e7a733-c604-4bd4-b8ea-bd48c80eab4d">&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;
## What is it?
LF-Timegate is a time measurement device developed to assist with Line Follower and Line Follower Drag competitions during the [XV ROBOTIC ARENA](https://roboticarena.pl/). It features circuit lap measurements and sprint measurements in one package with ±1ms accuracy.

![rect22-7](https://github.com/user-attachments/assets/2b5adb61-78eb-4406-bd00-0229d2a5dba9)

### Measurement modes:
<img align="center" height="160" src="https://github.com/user-attachments/assets/14b047e1-3b21-480e-b701-b1e88d9d197a">
<img align="center" height="160" src="https://github.com/user-attachments/assets/b293a596-0de7-4218-8f7d-6d8abdd7de3b">


For more information, read the [setup guide](https://github.com/ArthorH/LF-Timegate-REVA/blob/main/LF-Timegate-Setup-Guide.pdf).

## What MCU does it use?
None.

![image](https://github.com/user-attachments/assets/473d654d-c87e-4e9f-868d-7d7ecc76e5cd)

To ensure reliability and simplicity, it utilizes 10 CMOS 4000 ICs to make all the magic happen.  

Also check out new drop in replacement [sensors](https://github.com/ArthorH/Simple-IR-Light-barrier) 
## Device in action:
[In this video](https://www.youtube.com/watch?v=xdkL_AgzkSc)

<img align="center" height="220" src="https://github.com/user-attachments/assets/8788d20a-acbb-4e5f-97fc-0c9bf5c77299">&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 
<img align="center" height="220" src="https://github.com/user-attachments/assets/cb4966d3-725b-4cf5-bda3-bf1a30326bdd">&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 
<img align="center" height="600" src="https://github.com/user-attachments/assets/bfb66d14-5c6c-4270-8d43-93c3d3f25b9d">&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 
## Caution:
It is not recommended to manufacture this version (REV A) as it has 10 errors on the PCB. They are fairly simple and fixable as shown here:

#### Error in state machine 
<img align="center" height="160" src="https://github.com/user-attachments/assets/a0aee744-cc08-4c6b-b303-2f296a8f9929">&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 
<img align="center" height="160" src="https://github.com/user-attachments/assets/43e30967-946e-4c76-8b30-b151a21fcf93">&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 
<img align="center" height="160" src="https://github.com/user-attachments/assets/87d12fee-ff72-4789-b063-e5ceea5e3cda">&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 




## Authors
[Artem Horiunov](https://github.com/ArthorH) - schematic (state machine) and layout

[Dominik Pluta](https://github.com/Dominik-Workshop) - ir receivers and schematic
