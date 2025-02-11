# ShortCircuitMLTask

<h1>Task 1 : Linear Regression model for predicting premium amount</h1>

<h3>This task was accomplished using Multiple Linear Regression with Scikit Learn Library</h3>
<ul>
  <li>The First step was to cleanup and analyze the data using numpy and pandas which led to the conclusion :
  <ol>
    <li>
      There were no null values in the dataset
    </li>
    <li>
      There were 2 duplicates in the dataset
    </li>
  </ol>
  </li>
  <li>
    The Second step was to encode the labels into numeric values using sklearn preprocessing to avoid datatype errors during model training
  </li>
  <li>
    The Data was then split into 80% training and 20% testing sets using train_test_split from sklearn
  </li>
  <li>
    The Model was fit and appropriate evaluation metrics were calculated
  </li>
  <li>
    The Regression line was drawn between max and min pred comparing with actual values
  </li>
</ul>


<h1>Task 2 : Image Classification using Convolutional Neural Networks with Tensorflow</h1>

<h3># This task was accomplished using Tensorflow and CNN was chosen over just ANN dues to some obvious advantages</h3>
<h2>Addition of feature selection layer and Pooling Layer (Convolution Layers) help to dramatically improve model accuracy in cases where images are not ust simple images like doodles . 
This Also reduces Model training time per epoch by reducing the number of perceptrons to reach the same or better accuracy as compared to just ANN.
</h2>

<ul>
  <li>
    The First step was to import the data and to normalize it. The default data was a 3D array containing the resolution and the color per pixel of the image , it is necessary to divide the matrix by 255 to normalize it because the color values range from 0-255.
  </li>
  <li>
    The Convolutional Neural Network was created using 2 Convolution Layers and 2 Pooling Layers followed by 4 Dense perceptron Layers which gave softmax output.
  </li>
  <li>
    The Model was fit and evaluated based on loss and accuracy
  </li>
  <li>The Confusion Matrix and ROC(1 vs all) curve was plotted for better visualization .</li>
</ul>
