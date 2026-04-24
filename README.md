Software I wrote to help design a radiator core for UBR29. 

Rad_Spec_Software is the original code, for pure water rads.
Cooling_Sythsis is for pure water, glycol, engine oil, and air to air heat exchangers, all interacting with inlet air.
I made the latter to fix all the old bugs left in Rad_Spec_Software, and to allow for a bigger variety of design considerations.

Equations in this are taken mostly from the Thermex data sheet that UBRacing was provided with, albeit with a few exceptions.
These are as follows : 
mewweg(c) => data from https://www.engineeringtoolbox.com/ethylene-glycol-d_146.html 
altered ha equation derived from : https://www.sciencedirect.com/topics/engineering/colburn-factor 
effectiveness equation taken from : https://innovationspace.ansys.com/courses/wp-content/uploads/sites/5/2021/02/LT4C3-Lesson4-Handout-NT.pdf
Pressure drop equation set for intercoolers from : https://tfaws.nasa.gov/TFAWS07/Proceedings/TFAWS07-1016.pdf
