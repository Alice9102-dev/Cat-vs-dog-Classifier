 **Cat vs Dog Classifier**



Hello!  

This is a simple binary image classification model that predicts whether the input image is of a cat or a dog.



---



**📥 How to Get the Dataset**



For this project, I downloaded the dataset from Kaggle using their API.



**Steps to download:**

1\. Go to \[Kaggle](https://kaggle.com)

2\. Click on your profile → Account Settings

3\. Scroll down and click "Create New API Token" — this will download a file called `kaggle.json`

4\. Upload `kaggle.json` into your project folder

5\. Run the code — the data will be downloaded automatically



---



**How to Install Dependencies**



If you don’t have the required libraries, you can install them using:



**```bash**

pip install <library\_name>

**in Jupiter or Colab:**

&nbsp;

!pip install <library\_name>





**How to Test the Model?**



There are sample test images shown in the last section of the notebook/script to visualize model performance.



NOTE: The model will not run fully out-of-the-box unless you have the same dataset.

To test it manually:



Upload your own set of cat/dog images



Make sure to resize the images to the same shape the model expects



Replace the image path in the test section and observe the predictions



**Model Details:**

The model is a simple binary classifier



It assigns either a 0 or a 1 to indicate cat or dog



Please check the printed output or labels to interpret results



