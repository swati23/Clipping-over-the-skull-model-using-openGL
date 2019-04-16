# Clipping-over-the-skull-model-using-openGL

# The steps covered in model clipping till now are as follows:

1. Clipping of model using clipping plane constant in eye coordinate system. Internal details of the model are thus visible.

2. The clipping plane can be moved parallel to itself using left and middle mouse clicks for taking a section at the desired location. The step size of movement is 0.1

3. Determining and displaying the world coordinates corresponding to mouse click screen coordinates. The calculated world coordinates are stored as an array of tuples in a vector. These tuples are then used to create glVertex3f points for rendering in the window along with the model.
Two files are attached here. These two files should be kept in the same folder. To play the file the html file needs to be opened in a browser with flash player installed. 
