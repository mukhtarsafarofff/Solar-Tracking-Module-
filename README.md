This solar tracker is  a system that positions an object at an angle relative to the Sun.Here i have used LDR to detect the presence of light / measuring the intensity of light. In This circuit  I can  adjust the threshold (sensitivity) of digital output by tuning the on-board variable resistor (potentiometer). Simple usage as it is the digital output, so you will know is the light present and decide what to do with it.L293D  IC is a medium power motor driver perfect for driving DC Motors and this driver  greatly simplifies and increases the ease with which you may control motors, relays, etc from micro-controllers.  It can drive motors up to 12V with a total DC current of up to 600mA.When LDR2 receives more light than LDR1, it offers lower resistance than LDR1, providing a high input to comparators A1 and A2 at pins 4 and 7, respectively. As a result, output pin 1 of comparator A2 goes high to rotate motor M1 in one direction (say, anti-clockwise) and turn the solar panel. When LDR1 receives more light than LDR2, it offers lower resistance than LDR2, giving a low input to comparators A1 and A2 at pins 4 and 7, respectively.As the voltage at pin 5 of comparator A1 is now higher than the voltage at its pin 4, its output pin 2 goes high. As a result, motor M1 rotates in the opposite direction (say, clock-wise) and the solar panel turns.Similarly, LDR3 and LDR4 track the sun along Y axis.

Dieser Solartracker ist ein System, das ein Objekt relativ zur Sonne ausrichtet. Hier habe ich LDR verwendet, um die Anwesenheit von Licht zu erkennen bzw. die Lichtintensität zu messen. In diesem Schaltkreis kann ich die Schwelle (Empfindlichkeit) des digitalen Ausgangs durch Justieren des an Bord befindlichen variablen Widerstands (Potentiometer) einstellen. Die Verwendung ist einfach, da es sich um einen digitalen Ausgang handelt, sodass Sie erkennen können, ob Licht vorhanden ist und entscheiden können, was damit zu tun ist. Der L293D IC ist ein mittelstarker Motortreiber, der perfekt für das Ansteuern von Gleichstrommotoren geeignet ist, und dieser Treiber vereinfacht und erhöht die Benutzerfreundlichkeit, mit der Sie Motoren, Relais usw. von Mikrocontrollern aus steuern können.


