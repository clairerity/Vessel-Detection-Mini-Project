# Vessel-Detection-Mini-Project
This is the repository for the mini-project "Reduction of False Positives in Vessel Detection using HSV-based Thresholding"

This is our final mini-project for the subject CS282 (Computer Vision) at the University of the Philippines- Diliman.

Instructions:
1. Read concept behind the project (Read the slides and journal provided)
2. Test the program using Jupyter Notebook

OPTION 1: Retrain the model
a. Add the path of the training images provided ("Vessel" and "Not Vessel") as positive and negative images respectively under the "Fetch Dataset" cell.
b. Run all cells until 3), during feature extraction, you can choose whether to use HOG only (3A), LBP only (3B) or HOG + LBP (3C), CHOOSE ONLY 1 (don't run all or else it will automatically run HOG+LBP). 
c. After feature extraction, run 4) and 5)
d. Save the model by running 6)
e. Add path where you stored the trained model in "Object Detection Proper"
f. Add the filename of the image that you want to use for detection under "img_orig"
g. Run all remaining cells (NOTE: you have to comment out one of the features within the "Object Detection Proper" cell under the comment "calculate HOG and LBP" if you want to use only 1 feature)

OPTION 2: Use trained model
a. Add path where you saved the "Ship_Detection.npy" file to the "Object Detection Proper" cell
b. Do option 1's steps f and g

* Sample images are provided that users can use for testing the model. The default trained model is HOG only.
* For the post-processing step, you can adjust the threshold (thresh_up and thresh_down)

For questions or more info, please contact the author or visit https://github.com/clairerity/Vessel-Detection-Mini-Project
