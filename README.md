# CS350-Final-Project

Summarize the project and what problem it was solving.
  This project uses a thermostat to update/read temperature settings and it also uses buttons to increase or decrease the temperature. It's basically an embedded system to connect a thermostat to the cloud via Wi-Fi using a TI(Texas Instrument) board. It reads room temperature using I2C, LED to indicate thermostat is on/off using GPIO, detects button pressing using GPIO interrupts, and UARTS to display and recieve/transmit data.
The other project consists of blinking an LED using button interrupt from another assignment.

What did you do particularly well?
For this project, I do not feel that I done well at all. I should have been more attentive to the ZyBooks readings but I had a hard time understanding how to basically put it all together. I did on the other hand enjoy learning how to blink the LEDs. For the other artifact(blinking LED), I feel that I had a very good understanding of the material and was able to blink the LEDs based on the instructions. Also, the state machine documentaion and the task scheduler documentation helped when it came to writing the code to make the LEDS works and button intterrupts.

Where could you improve?
I feel that I can improve with understand how to implement the task scheduler using the enumerators. I had a hard time grasping this concept.

What tools and/or resources are you adding to your support network?
Other tools included TI documentation, open declarations pages, and Zybooks helped out. UARTs are efficient and used to transmit and recieve data based on baud rate which makes transmission deployable without data loss. 

What skills from this project will be particularly transferable to other projects and/or course work?
Skills learned from this project are definately the state machine/task scheduler documentaation. It helps out to make a plan before working on the actual code. This keeps the project in line. Using comments help to understand what you are writing especially dealing with a large amount of code. You can always looks at the comments to undertsna what the code is doing. 

How did you make this project maintainable, readable, and adaptable?
I made this project maintainable, readable and adaptable by using the industry's best practices using comments, initializing variable, and by using comments. The code is formatted properly and easy to read and follow. 
