# Gesture Phase Segmentation Classification with In-Depth Machine Learning Model Comparisons

The overall question that was being assessed through this project was whether **gestures be classified to reveal information about semantics within what is being said in a discourse.**

dataset: https://archive.ics.uci.edu/ml/datasets/gesture+phase+segmentation

This project was assigned for one of my Postgraduate classes called *Learning From Data* at Durham Univeristy. 

With the help from *Sao Paulo Research Foundation*, researchers were able to gather and construct a dataset called Gesture Phase Segmentation, focusing on three different users’ gestures when telling a story on three different comic strips. Microsoft Kinect sensor recorded these users to obtain: an image, timestamp, and positions (x, y, z) of six articulation points. This information was stored within the researchers’ 7 raw data files, while the 7 processed data files contained recorded x, y, z coordinates of the vectorial velocity, scalar velocity and vectorial acceleration of four articulation points.

To examine this dataset further with various Machine Learning classifiers, the dataset needed to be restricted to a more appropriate size. The dataset was narrowed down from three users and three comic strips (9,900 instances) to User A with all three comic strips (4,845 instances). The dataset will also be narrowed down by attributes by choosing to work with the processed data files only, leaving this modified dataset to only contain 32 numeric attributes and a class attribute. The 32 attributed also contained correlated features so this continued the attributes reduction to 12. The class attribute contains the five different phases that a gesture movement is categorized as; rest, preparation, stroke, hold and retraction. This is an important factor when constructing classification models because it permits training and testing data, as will be seen later on with Bayesian and Neural Network classifiers. 
