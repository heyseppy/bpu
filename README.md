# bpu
the breadboarded programmable unit


### Architecture 

The architecture for the BPU is based on a classical Von Neumann machine. Meaning that behind it is one base memory unit containing the operations and relevant addresses. 


### Functions

- 000 XXX (**ADD-C**  add constant XXX to the accumulator) 
- 001 XXX (**ADD-M**  add memory value *(addr XXX)* to the accumulator) 
- 010 XXX (**BRA**  branch to address XXX) 
- 011 XXX (**STR**  store accumulator value to memr[XXX]) 
- 100 *** (**CLR**  clear accumulator) 
- 101 XXX (**BRIF**  branch to beginning if acc == XXX) 
- 110 XXX (**SUB-C**  subtract constant XXX to the accumulator) 
- 111 XXX (**DBG**  debug by turning all lights on) 