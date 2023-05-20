# simulink-range-scaling-block
Simulink block to easily scale an input to a given range

[![View Scale on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/6353-scale)

This block linearly scales an input vector ranging from xmin to xmax to an output vector ranging from ymin to ymax.

The four parameters xmin, xmax, ymin, ymax can be themselves vectors (or matrices), so each element can be scaled independently from the others.

The function performed is just a simple affine transformation, but it is used often and widely (sensors, actuators, DAC, ACD ...).
This block allows to perform the transformation just entering the desired range, so you don't have to calculate anything.
