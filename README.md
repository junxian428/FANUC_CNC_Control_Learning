# FANUC_CNC_Control_Learning

![image](https://raw.githubusercontent.com/junxian428/FANUC_CNC_Control_Learning/main/HelloWorldProgram.jpg)

This appears to be a sequence of G-code commands, which are instructions used to control CNC (Computer Numerical Control) machines like mills, lathes, and 3D printers. Let's break it down step by step:

1. `00013;`: This could be a line number or a program identifier. It depends on the specific CNC system being used.

2. `;`: This is usually a comment delimiter, meaning anything after it on the same line is ignored by the CNC machine and is meant for human readability.

3. `M5;`: This command turns off the spindle or the main rotational axis of the machine. 

4. `T0505;`: This might be a tool change command, where it's selecting a tool, though without more context it's hard to say what the specific tool might be.

5. `M25;`: This command typically pauses the machine until a cycle start button is pressed. This is often used for manual operations.

6. `G0CM110.0;`: This could be a rapid traverse command, moving the machine to coordinates specified in mode CM (not a standard G-code mode, might be a custom mode specific to a particular machine). The coordinates are X=110.0.

7. `M78;`: This is another command that's specific to the machine or its control system. Without more context, it's hard to say what it does.

8. `G0X50.0Y0Z-25.0;`: This is another rapid traverse command, moving the machine to the coordinates X=50.0, Y=0, Z=-25.0.

9. `;`: This is again a comment delimiter.

10. `X38.0F200;`: This seems to be a linear movement command, moving the machine to the X coordinate 38.0 at a feed rate of 200 units per minute.

11. `X36.0F10;`: Another linear movement command, moving to X coordinate 36.0 at a slower feed rate of 10 units per minute.

12. `G4P100;`: This is a dwell command, causing the machine to pause for 100 milliseconds.

13. `G0X100.0;`: Rapid traverse to X coordinate 100.0.

14. `M205;`, `M26`, `M79`, `M55`: These are machine-specific commands, without more context it's hard to determine their exact function.

15. `G28U0W0V0;`: This command is typically used for returning the machine to its reference or home position.

16. `M30;`: This is the end of program command.

Again, without more context about the specific machine and its configuration, some of these commands are difficult to interpret precisely.
