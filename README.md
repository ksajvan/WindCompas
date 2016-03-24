# WindCompas
CustomView control, simulating wind compas
CustomView, draws circle with four sides of the world (North, East, South and West) and pointer pointing to the North. 
This is just a show case for purpose of the udacity sunshine android course.
If used in real app, update method should be called. It takes two arguments, wind direction (angle in degrees readed from json file) and short version of the world side ("N" for North, or "SW" for South West for example)
CompassView will use direction information to highlight (paint in red) current world side and angle to point the line in proper direction.
