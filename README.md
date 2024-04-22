This solar tracker is  a system that positions an object at an angle relative to the Sun.Here i have used LDR to detect the presence of light / measuring the intensity of light. In This circuit  I can  adjust the threshold (sensitivity) of digital output by tuning the on-board variable resistor (potentiometer). Simple usage as it is the digital output, so you will know is the light present and decide what to do with it.L293D  IC is a medium power motor driver perfect for driving DC Motors and this driver  greatly simplifies and increases the ease with which you may control motors, relays, etc from micro-controllers.  It can drive motors up to 12V with a total DC current of up to 600mA.When LDR2 receives more light than LDR1, it offers lower resistance than LDR1, providing a high input to comparators A1 and A2 at pins 4 and 7, respectively. As a result, output pin 1 of comparator A2 goes high to rotate motor M1 in one direction (say, anti-clockwise) and turn the solar panel. When LDR1 receives more light than LDR2, it offers lower resistance than LDR2, giving a low input to comparators A1 and A2 at pins 4 and 7, respectively.As the voltage at pin 5 of comparator A1 is now higher than the voltage at its pin 4, its output pin 2 goes high. As a result, motor M1 rotates in the opposite direction (say, clock-wise) and the solar panel turns.Similarly, LDR3 and LDR4 track the sun along Y axis.

Dieser Solartracker ist ein System, das ein Objekt in einem Winkel relativ zur Sonne positioniert. Hier habe ich LDR verwendet, um das Vorhandensein von Licht zu erkennen/die Lichtintensität zu messen. In dieser Schaltung kann ich den Schwellenwert (Empfindlichkeit) des digitalen Ausgangs anpassen durch Einstellen des integrierten variablen Widerstands (Potentiometer). Einfache Bedienung, da es sich um den digitalen Ausgang handelt, sodass Sie wissen, ob das Licht vorhanden ist, und entscheiden können, was Sie damit tun möchten. Der L293D IC ist ein Motortreiber mittlerer Leistung, der sich perfekt für den Antrieb von Gleichstrommotoren eignet. Dieser Treiber vereinfacht und erhöht die Benutzerfreundlichkeit erheblich kann Motoren, Relais usw. über Mikrocontroller steuern. Es kann Motoren bis 12 V mit einem Gesamtgleichstrom von bis zu 600 mA antreiben.
