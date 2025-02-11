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
