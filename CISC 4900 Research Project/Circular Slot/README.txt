--Task--

Create a 2" diameter circle and 1/2" deep. The same limitations with movement are required as creating the straight line "slot". The same limitations stand with only allowing 0.03" at a time on the Z axis and 1/16" horizontally (on 
the X axis).

--Solution--

I start with moving the mill to X 1 and Y 2 and from there I set up a arc mode movement which creates the first circle on 
the material with a radius of 0.9375. After the full circle is done, I move horizontally 1/16" and again create another circle but with a new radius (old radius - 0.0625). 
This process is repeated and thoroughly explained within my documentation. Once I reach the "center", I have achieved a completely leveled 2" diameter circular slot. 
To achieve the depth of 1/2" I repeat the process decrementing the Z axis by -0.03" each time with the last time being -0.02" to achieve the proper 1/2" depth required. 
The "length" of the circle reaches from Y axis value 1.06 to Y axis value 2.9375. Adding a -0.0625 and 0.0625 respectively is a 2" long diamter. The same is achieved for the X from X axis value 1 to X axis value 2.875. 
Adding the excess will give you a 2" long diamter as well, thus achieving all requirements. (In pictures the end points are rounded by the simulation but are programmed to go to the specific lengths.)
