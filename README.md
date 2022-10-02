# Computer-Vision-Track
Codevita Live CV internship Tasks
Task1: Edge and Contour Detection Model
Task2: Hand Gesture Detection
Task3: Face Detection Model
Edges are where there is discontinuties and objects are separated. It is done using Canny Edge Detection.
(The Canny edge detector is an edge detection operator that uses a multi-stage algorithm to detect a wide range of edges in images. It was developed by John F. Canny in 1986.)



Steps involoved in Canny Edge Detection:

1. Apply Gaussian filter to smooth the image in order to remove the noise
2. Find the intensity gradients of the image
3. Apply gradient magnitude thresholding or lower bound cut-off suppression to get rid of spurious response to edge detection
4. Apply double threshold to determine potential edges
5. Track edge by hysteresis: Finalize the detection of edges by suppressing all the other edges that are weak and not connected to strong edges.




In this project we will use the tools provided with opencv to do all these steps faster.
