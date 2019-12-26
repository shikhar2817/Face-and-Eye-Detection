# Face-and-Eye-Detection

The Detection is done by aspect ration.
If the Aspect ratio is found between 0.75 and 1.30 it draws a circle around it.

Aspect ratio Calculation :
  Aspect ratio = width/hight 
 
Circle is Drawn 0.5*width and 0.5*height from the Centre point.

To Execute your system must have OpenCV:
  For compilation :
    Terminal Code : g++ main.cpp -o output `pkg-config --cflags --libs opencv`
  For Running :
    Terminal Code : ./output
    
If the program is not executing :
  * the problem must be the location of hpp files in the includes.
  * verify the path and try again it will defently work.
  
