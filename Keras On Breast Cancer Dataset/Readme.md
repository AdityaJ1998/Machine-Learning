# Tensorflow on Breast Cancer Dataset #

1. Added a first 'Dense' layer with 32 units and relu activation function.
2. Added a second 'Dense' layer with 16 units and relu activation function. 
3. The ouput layer had just 1 unit due to binary output and sigmoid activation function.
4. Compiled the model with Adam Optimiser & loss function 'binary_crossentropy'.
5. Fitted the model with 20 epochs and batch_size of 50.
6. Evaluated results

## Dataset Characteristics ##
* Number of Instances: 569
* Number of Attributes: 30 numeric, predictive attributes and the class
* Attribute Information:
 	* radius (mean of distances from center to points on the perimeter)
  * texture (standard deviation of gray-scale values)
  * perimeter
  * area
  * smoothness (local variation in radius lengths)
  * compactness (perimeter^2 / area - 1.0)
  * concavity (severity of concave portions of the contour)
  * concave points (number of concave portions of the contour)
  * symmetry
  * fractal dimension (“coastline approximation” - 1)

## The accuracy achieved was 98.24%. ##


