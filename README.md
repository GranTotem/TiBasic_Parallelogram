To begin with drag the file PRALOGRM.8xp to the TI-84 Device Explorer to flash the program to the calculator

Next do the same with the Pictuce: Pic2

To use the program run it and enter the coordinates in the following order:

top left - top right - bottom left - bottom right

Now select prove and the program should show you the slope and next the lengths.

************************************************************************************************************************

ClrHome

Goto 4

Lbl 5

ClrHome

Menu("MENU","PROVE",1,"NEW VARS",2,"EXIT",3,"HELP",6)

Lbl 4

Input "X 1=",A

Input "Y 1=",C

Input "X 2=",B

Input "Y 2=",D

Input "X 3=",E

Input "Y 3=",G

Input "X 4=",F

Input "Y 4=",H


Goto 5

Lbl 1

(D-C)üI

(B-A)üS

I/SüS


(H-G)üJ

(F-E)üT

J/TüT


(G-C)üK

(E-A)üU

K/UüU


(H-D)üL

(F-B)üV

L/VüV


ð((B-A)Ü+(D-C)Ü)üX

ð((F-E)Ü+(H-G)Ü)üY

ð((G-C)Ü+(E-A)Ü)üZ

ð((H-D)Ü+(F-B)Ü)üÁ

Disp "SLOPE 1: ",S,T

Disp "SLOPE 2: ",U,V

Pause 

ClrHome

Disp "DISTANCE 1: ",X,Y

Disp "DISTANCE 2: ",Z,Á

Pause 

Goto 5

Lbl 3

Return

Lbl 2

Goto 4

Lbl 6

StorePic 9

AxesOff

RecallPic 2

Pause 

ClrDraw

AxesOn

Goto 5

************************************************************************************************************************

Note: In the source code above store as (button STO>) is shown as: / ü / and square root (2nd x2) is shown as: / ð /
