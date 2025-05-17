# **EMNIST Dataset**

Dataset Format 

• Binary (8 bit format)

• CSV

  • Each row is separate image

  • 785 column

  • First column = class_label

  • Each column after represents one pixel value (784 total for a 28 x 28 image)

• More detail see : https://www.kaggle.com/datasets/crawford/emnist/data

• Focus on Letters Datasets

• The EMNIST Letters dataset merges a balanced set of the uppercase and lowercase letters into a single 26-class task.

in exam, do on :

**1. Dataset Preparation**

• Use 2600 samples only for this exam (make sure classes are ballance)

• Each class has 100 samples

• Process dataset (binary or CSV) and visualize the image

• Shuffle datasets before processing

• Leave One Out Cross Validation (LOOCV) - Split Dataset

• 80% for training

• 20% for testing

**2. Feature Extraction**

• Use HOG Feature Extraction

• Change the default parameters

• orientation

• pixels_per_cell

• cells_per_block

**3. Classification**

• Use Support Vector Machine (SVM) for classification

• Change default SVM parameters

• Kernel type

• Regularization (C)

• Gamma

• Measure training performance

• Use Grid Search Techniques to find the best performance

**4. Evaluation**

• Evaluate on train (80%) and test datasets (20%)

• Performance metrics

• accuracy

• precision

• recall

• F1-score
