This is a relatively simple circuit with 2 ICs for glue logic, a 74LS32 and a 74LS266. What this circuit does is swap the addressing of PORTA and PORTB on the MOS 6526 CIA chip. 

This is a work around if you have a partially failed chip. I had Pin 6 fail on my CIA (joystick fire button), which is part of PORTA. With this work around I was able to put the failed chip in second CIA socket that controls the IEC Bus, at the loss of the USERPORT being connected.

