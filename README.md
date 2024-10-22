# Hyperspectral-Image-Classification

# Salinas Valley Dataset:

1. Import the essential libraries by running the first block of the code [1].
2. Coordinate Attention Block is defined in second block of code. Run the code [2].
3. Multi-Scale Fusion Block is defined in [3]. Run the third block of code [3].
4. The Main Model for Hyperspectral Fusion is defined in code block [4]. Run this cell.
5. Custom Dataset for Hyperspectral images with patches is defined in code block [5]. Run this cell.
6. Function to calculate metrics [OA: Overall Accuracy, AA: Average Accuracy and Kappa Values] is defined in code block [6]. Run this code block.
7. Salinas Valley Dataset is loaded in [7]. Here the dataset is split into Training: 300, Validation: 300 and Testing: Remaining for each class label.
8. Dataset is visualized in code block [8][9] for training data and [10][11] for ground truth images. Run these code cells.
9. Run code cell [12] for training the model on the Salinas dataset. Model is trained for 16 classes with input channels 204, epochs = 100, batch-size = 32 and lr = 3e-4.
10.Run code cell [13] for testing and evaluating the model for different window sizes [8,9,10,11,12] and subsequent values of the metrics are obtained.  
11. In case of error, check for the dependencies to be installed on your virtual environment.


# Pavia University Dataset:

1. Import the essential libraries by running the first block of the code [1].
2. Coordinate Attention Block is defined in second block of code. Run the code [2].
3. Multi-Scale Fusion Block is defined in [3]. Run the third block of code [3].
4. The Main Model for Hyperspectral Fusion is defined in code block [4]. Run this cell.
5. Custom Dataset for Hyperspectral images with patches is defined in code block [5]. Run this cell.
6. Function to calculate metrics [OA: Overall Accuracy, AA: Average Accuracy and Kappa Values] is defined in code block [6]. Run this code block.
7. Salinas Valley Dataset is loaded in [7]. Here the dataset is split into Training: 300, Validation: 300 and Testing: Remaining for each class label.
8. Dataset is visualized in code block [8][9] for training data and [10][11] for ground truth images. Run these code cells.
9. Run code cell [12] for training the model on the Pavia University dataset. Model is trained for 9 classes with input channels 103, epochs = 100, batch-size = 32 and lr = 3e-4.
10.Run code cell [13] for testing and evaluating the model for different window sizes [8,9,10,11,12] and subsequent values of the metrics are obtained.  
11. In case of error, check for the dependencies to be installed on your virtual environment.


# Indian Pines Dataset:

1. Import the essential libraries by running the first block of the code [1].
2. Coordinate Attention Block is defined in second block of code. Run the code [2].
3. Multi-Scale Fusion Block is defined in [3]. Run the third block of code [3].
4. Model with Attention and Multi-scale fusion is defined in code block [4]. Run this cell.
5. Custom Dataset for Hyperspectral images with patches is defined in code block [5][6]. Run these cells.
6. Function to calculate metrics [OA: Overall Accuracy, AA: Average Accuracy and Kappa Values] is defined in code block [7]. Run this code block.
7. Indian Pines Dataset is loaded in [7]. Here the dataset is split into Training: 8,105,100,50,80,100,10,40,8,110,110,100,40,100,80,20, Validation: 4,105,100,50,80,100,4,40,4,110,110,100,40,100,80,10 and Testing: Remaining for each corresponding class label.
8. Run code cell [9] for training the model on the Indian Pines dataset. Model is trained for 16 classes with input channels 200, epochs = 100, batch-size = 10 and lr = 3e-4.
10.Run code cell [10][11] for testing and evaluating the model for different window sizes [17,19,21] and subsequent values of the metrics are obtained.  
11. In case of error, check for the dependencies to be installed on your virtual environment.
