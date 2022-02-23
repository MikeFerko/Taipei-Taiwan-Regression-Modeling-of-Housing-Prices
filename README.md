<!DOCTYPE html>
<head>Real Estate Evaluation of housing prices in Taipei Taiwan</head>
<body>
  <div>
    <p>
     <ul>
       <li>We are using the same sequential MLP model used for the Saddle Point and Ackley Function preditctions.</li>
     </ul>
    </p>
    <p align="center">
     <a href="https://drive.google.com/file/d/17p5fgVgv836Nup1Jq5vYwrFuBrS3THVM/view?usp=sharing">
     <img src="https://github.com/MikeFerko/MikeFerko/blob/main/images/MLPModel.png" width="50%" height="50%">
     </a>
     <br>Multiple Linear Perceptron (MLP) Model</br>
    </p>
    <p>We will be <a href="https://drive.google.com/file/d/1vAsnXHDkRoNFSS2KrWP39lFF4fS3J43O/view?usp=sharing">examining real estate valuation</a> which will help us understand where people tend to live in a city. The higher the price, the greater the demand to live in the property. Predicting real estate valuation can help urban design and urban policies, as it could help identify what factors have the most impact on property prices. Our aim is to predict real estate value, based on several features.
    </p>
    <br></br>
    <p>
    <ul>
      <li>Regression MLP Machine Learning on Taipei Taiwan Algorithm:</li>
      <ol type="1">
        <li>Load the Real estate valuation data set</li>
        <li>Independent feature vector containing:</li>
        <ol type="1" start="2">
          <li>X2 house age</li>
          <li>X3 distance to the nearest MRT station</li>
          <li>X4 number of convenience stores</li>
          <li>X5 latitude</li>
          <li>X6 longitude</li>
        </ol>
        <li>Train/Test split the data at a ratio of 80:20, respectively</li>
        <li>Min/Max Scale the dataset with a range of 0 to 1</li>
        <li>Normalise the scaled features</li>
        <li>Regression MLP Model Parameters:</li>
        <ul>
          <li><a href="https://en.wikipedia.org/wiki/Stochastic_gradient_descent">Stochastic Gradient Descent optimizer</a></li>
          <ul>
            <li>Learing Rate = 0.1</li>
            <li>Exponential Decay Factor = 0</li>
            <li>Momentum = 0.1</li>
           </ul>
          <li><a href="https://en.wikipedia.org/wiki/Mean_squared_error">Mean Square Error Loss Function</a></li>
          <li>Train Duration: 50 Epochs</li>
          <li>Batch Size = 10</li>
        </ul>
        <li>Create a predicted House Price Prediction of the unit area from the Regression MLP trained Neural Network</li>
        <li>Plot the Results</li>
      </ol>
    </ul>
    </p>

  <p align="center">
    <a href="https://drive.google.com/file/d/1i49EBOacHkSxA84ghQZCQ3JSvItULceT/view?usp=sharing">
    <img src="https://github.com/MikeFerko/MikeFerko/blob/main/images/MLPRegressionLoss.png" width="50%" height="50%">
    </a>
    <br>Regression MLP Model Loss</br>
  </p>

  <p align="center">
    <a href="https://drive.google.com/file/d/1i49EBOacHkSxA84ghQZCQ3JSvItULceT/view?usp=sharing">
    <img src="https://github.com/MikeFerko/MikeFerko/blob/main/images/RegressionPrediction.png" width="50%" height="50%">
    </a>
    <br>Regression MLP Predictions</br>
  </p>

</div>
</body>
</html>
