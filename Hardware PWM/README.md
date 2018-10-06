# Hardware PWM
For this part of Lab 3 the code will increment the pulse width of the LED ini the same way it is done in the software section.  Initially it is 50% brightness, then incremented in steps of 10% until it reaches 100% where it is reset back to 0%.  This time hardware PWM was used.  Hardware is used by setting the timers in reset, set or toggle mode.  Both boards will have the LED brigtness increased with a seperate LED to show it has been done when the button is pressed.  

## Implementation on both boards
The implementation on both boards is the same besides the port and pin numbers.  There is a difference between the timers.  The FR2311 does not use timer A because it does not have it like the G2.  Instead timer b is used for the FR2311.  The timers function basically the same so syntax is very similar.
