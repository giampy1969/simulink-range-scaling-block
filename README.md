# simulink-range-scaling-block
Simulink block to easily scale an input to a given range

This block linearly scales an input vector ranging from xmin to xmax to an output vector ranging from ymin to ymax.

The four parameters xmin, xmax, ymin, ymax can be themselves vectors (or matrices), so each element can be scaled independently from the others.

The function performed is just a simple affine transformation, but it is used so often and so widely (sensors, actuators, DAC, ACD ...), that i think it should have a place under the standard Math Operations library in Simulink.
