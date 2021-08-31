# DR-Preprocessed-Resized-Dataset
The dataset contains images of **Diabetic Retinopathy** stages and each stage has its respective folder.
The images were taken from three different sources and were merged together.
* APTOS2015 Competition (Kaggle) https://www.kaggle.com/c/diabetic-retinopathy-detection
* APTOS2019 Competition (Kaggle) https://www.kaggle.com/c/aptos2019-blindness-detection
* Messidor-2 Dataset https://www.adcis.net/en/third-party/messidor2/

# Operations Performed on the Dataset
Each images were first preprocessed using OpenCV in Python based Ben Graham implementation in a APTOS2015 Kaggle competition where he achieved 1st position.
In the preprocessing step,
* First the image is blurred using Gaussian Filter.
* Followed by element-wise subtraction.

Then each image were resized to 256x256x3 and split into training and test sets.
