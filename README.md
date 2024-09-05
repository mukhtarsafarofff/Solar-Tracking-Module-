(ENG) This solar tracker is  a system that positions an object at an angle relative to the Sun.Here i have used LDR to detect the presence of light / measuring the intensity of light.  In This circuit  I can  adjust the threshold (sensitivity) of digital output by tuning the on-board variable resistor (potentiometer).  Simple usage as it is the digital output, so you will know is the light present and decide what to do with it. L293D  IC is a medium power motor driver perfect for driving DC Motors and this driver  greatly simplifies and increases the ease with which you may control motors, relays, etc from micro-controllers.   It can drive motors up to 12V with a total DC current of up to 600mA.When LDR2 receives more light than LDR1, it offers lower resistance than LDR1, providing a high input to comparators A1 and A2 at pins 4 and 7, respectively.

(DEU) Dieser Solartracker ist ein System, das ein Objekt relativ zur Sonne ausrichtet. Hier habe ich LDR verwendet, um die Anwesenheit von Licht zu erkennen bzw. die Lichtintensität zu messen. In diesem Schaltkreis kann ich die Schwelle (Empfindlichkeit) des digitalen Ausgangs durch Justieren des an Bord befindlichen variablen Widerstands (Potentiometer) einstellen. Die Verwendung ist einfach, da es sich um einen digitalen Ausgang handelt, sodass Sie erkennen können, ob Licht vorhanden ist und entscheiden können, was damit zu tun ist. Der L293D IC ist ein mittelstarker Motortreiber, der perfekt für das Ansteuern von Gleichstrommotoren geeignet ist, und dieser Treiber vereinfacht und erhöht die Benutzerfreundlichkeit, mit der Sie Motoren, Relais usw. von Mikrocontrollern aus steuern können. Er kann Motoren bis zu 12V mit einem gesamten Gleichstrom von bis zu 600mA antreiben. Wenn LDR2 mehr Licht als LDR1 empfängt, bietet er einen geringeren Widerstand als LDR1 und liefert einen hohen Eingang an die Komparatoren A1 und A2 an den Pins 4 und 7.  Infolgedessen geht der Ausgangspin 1 des Komparators A2 hoch, um den Motor M1 in eine Richtung (sagen wir, gegen den Uhrzeigersinn) zu drehen und das Solarpanel zu bewegen. Wenn LDR1 mehr Licht als LDR2 empfängt, bietet es einen geringeren Widerstand als LDR2, was zu einem niedrigen Eingang an die Komparatoren A1 und A2 an den Pins 4 und 7 führt. Da die Spannung am Pin 5 von Komparator A1 jetzt höher ist als die Spannung an seinem Pin 4, geht sein Ausgangspin 2 hoch. Infolgedessen dreht sich Motor M1 in die entgegengesetzte Richtung (sagen wir, im Uhrzeigersinn) und das Solarpanel dreht sich. Ähnlich verfolgen LDR3 und LDR4 die Sonne entlang der Y-Achse.


