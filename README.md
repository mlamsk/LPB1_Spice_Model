# LPB1_Spice_Model

This is an LTSpice Model of the LBP-1 boost pedal. This is needed for deriving the closed form analytic solution to the LPB-1 guitar pedal and building a SPICE numerical simulation.

![LPB-1 Spice Model](https://github.com/mlamsk/LPB1_Spice_Model/blob/Reverse_Engineered_LPB1_Final/LPB1_Final_Model.PNG)


The schematic above of the LPB-1 boost pedal uses a transistor that is not a default transistor model within LTSpice. Therefore, a ".MODEL" Spice directive is needed to include the proper transistor. f

A list of ".MODEL" statements can be found using the link below:
[Standard BJT List](http://ltwiki.org/index.php?title=Standard.bjt)

Find your desired component, and create a ".MODEL" statement using a Spice directive.