# Knee-osteoarthritis-susceptibility-prediction
**Overview** </br>
</br>
This project uses a Convolutional Neural Network (CNN) to classify knee X-ray images for the prediction of osteoarthritis severity. It trains a deep learning model on labeled X-ray images using TensorFlow and Keras, then evaluates the model’s performance.

</br>

**Prerequisites** </br>
- Python 
- Google Colab or a local environment with TensorFlow and Keras installed
- Additional libraries: OpenCV, Numpy, Matplotlib, scikit-learn, mlxtend

</br>

**Dataset** </br>
- Normal
- Doubtful
- Mid
- Moderate
- Severe
<p><b>Images are stored in separate folders within /knee-project/MedicalExpert-I/knee-dataset/x-ray/.</b></p>
</br>

**Model Architecture** </br>
<p>The CNN model is implemented using Keras, comprising:</p>

- Convolutional layers with ReLU activation
- MaxPooling layers
- Dropout layers for regularization
- Dense layers leading to a final softmax layer for classification
</br>

**Results** </br>

- <b>Test Accuracy</b> and <b>Loss</b> after 100 epochs.
- <b>Sample Predictions</b> with both model predictions and correct labels.
- <b>Confusion Matrix</b> visualization for detailed error analysis.

</br>

**Dataset_Link** </br>

- <b>Link :</b> <href>https://data.mendeley.com/datasets/t9ndx37v5h/1</href>
</br>
