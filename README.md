![da](https://github.com/user-attachments/assets/72f89c5f-3965-4c38-af1a-255bf9265079)
## What is it?
LF-Timegate is a time measurement device developed to assist with Line Follower and Line Follower Drag competitions during the [XV ROBOTIC ARENA](https://roboticarena.pl/). It features circuit lap measurements and sprint measurements in one package with ±1ms accuracy.

![rect22-7](https://github.com/user-attachments/assets/2b5adb61-78eb-4406-bd00-0229d2a5dba9)

### Meashurement modes:
![rect2434123awefawe2-72-9](https://github.com/user-attachments/assets/14b047e1-3b21-480e-b701-b1e88d9d197a)
![path97](https://github.com/user-attachments/assets/b293a596-0de7-4218-8f7d-6d8abdd7de3b)


For more information, read the [setup guide](https://github.com/ArthorH/LF-Timegate-REVA/blob/main/LF-Timegate-Setup-Guide.pdf).

## What MCU does it use?
None.

![image](https://github.com/user-attachments/assets/473d654d-c87e-4e9f-868d-7d7ecc76e5cd)

To ensure reliability and simplicity, it utilizes 10 CMOS 4000 ICs to make all the magic happen.  

## Device in action:
![image](https://github.com/user-attachments/assets/8788d20a-acbb-4e5f-97fc-0c9bf5c77299)![image](https://github.com/user-attachments/assets/cb4966d3-725b-4cf5-bda3-bf1a30326bdd)
![image](https://github.com/user-attachments/assets/bfb66d14-5c6c-4270-8d43-93c3d3f25b9d)

[In this video](https://www.youtube.com/watch?v=xdkL_AgzkSc)

# Warning 
It is not recommended to manufacture this version (REV A) as it has 10 errors on the PCB. They are fairly simple and fixable as shown here:

#### Error in state machine 
<img align="center" height="180" src="https://github.com/user-attachments/assets/a0aee744-cc08-4c6b-b303-2f296a8f9929">&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 
<img align="center" height="180" src="https://github.com/user-attachments/assets/43e30967-946e-4c76-8b30-b151a21fcf93">&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 

#### Forgor pull-up :(((
![image](https://github.com/user-attachments/assets/87d12fee-ff72-4789-b063-e5ceea5e3cda)

Also, the schematic kinda detached itself from the PCB, so keep an eye on it. 

### NOTE:
I am currently in the midst of making a remastered version of this board with a fixed schematic and layout. Hopefully, I will finish it this year

<img align="center" height="300" src="https://github.com/user-attachments/assets/289c8711-deb6-4f8b-a31f-e3bd8505ad07">
<img align="center" height="300" src="https://github.com/user-attachments/assets/4a43e522-085f-4a19-8ab4-52f971afa949">

## Authors
[Artem Horiunov](https://github.com/ArthorH)

[Dominik Pluta](https://github.com/Dominik-Workshop)

## Used tools:
<img align="center" height="180" src="https://github.com/user-attachments/assets/7439b4e2-4956-4fe5-be43-aab39e68163c">&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;

