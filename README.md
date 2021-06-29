<h1>Neural Network Charity Analysis</h1>

<h2>Overview</h2>

<h3>Purpose</h3>
<p>
  The purpose of this analysis was to attempt to create a machine learning model with Tensorflow that can accurately predict whether an applicant will be successful if funded by the Alphabet Soup Co.
</p>

<h2>Results</h2>

<h3>Data Preprocessing</h3>

<ul>
  <li>What variable(s) are considered the target(s) for your model?
  <ul><li>The "IS_SUCCESSFUL" column was the target variable for this model.</li></ul></li>
  </ul>
  
<ul>
  <li>What variable(s) are considered to be the features for your model?
  <ul><li>The feature variables are as follows:<ul>
    <li>APPLICATION_TYPE</li>
    <li>AFFILIATION</li>
    <li>CLASSIFICATION</li>
    <li>USE_CASE</li>
    <li>ORGANIZATION</li>
    <li>STATUS</li>
    <li>INCOME_AMT</li>
    <li>SPECIAL_CONSIDERATIONS</li>
    <li>ASK_AMT</li></li></ul></li>
  </ul>
  
<ul>
  <li>What variable(s) are neither targets nor features, and should be removed from the input data?
  <ul><li>EIN and NAME were neither targets nor features and, thus, were removed from the input data.</li></ul></li>
  </ul>

<h3>Compiling, Training, and Evaluating the Model</h3>
<p>Four attempts were made at creating a neural network model that exceeded 75% accuracy.  Each below will answer the following questions
<ul>
  <li>How many neurons, layers, and activation functions did you select for your neural network model, and why?</li>
  <li>Were you able to achieve the target model performance?</li>
  <li>What steps did you take to try and increase model performance?</li>
  </ul>
  
<p align=center>
  <img src='https://github.com/tc9993/neural-network-charity-analysis/blob/main/Resources/attempt1_define.GIF?raw=true' alt='Attempt 1 Defined'><br>
  <b>Figure 1.1:</b> Attempt 1 Defined
</p>
<p align=center>
  <img src='https://github.com/tc9993/neural-network-charity-analysis/blob/main/Resources/attempt1_outcome.GIF?raw=true' alt='Attempt 1 Outcome'><br>
  <b>Figure 1.2:</b> Attempt 1 Outcome
</p>
<p><b>Attempt 1</b></p>
<p>The first attempt, to establish a baseline, used 2 hidden layers with the first consisting of 80 neurons, the second 30 (Figure 1.1).  Both hidden layers used ReLu as the activation, while the output used Sigmoid.  The outcome was an accuracy of 72.4%, below the 75% goal (Figure 1.2).
</p>

<p align=center>
  <img src='https://github.com/tc9993/neural-network-charity-analysis/blob/main/Resources/attempt2_define.GIF?raw=true' alt='Attempt 2 Defined'><br>
  <b>Figure 2.1:</b> Attempt 2 Defined
</p>
<p align=center>
  <img src='https://github.com/tc9993/neural-network-charity-analysis/blob/main/Resources/attemp2_outcome.GIF?raw=true' alt='Attempt 2 Outcome'><br>
  <b>Figure 2.2:</b> Attempt 2 Outcome
</p>
<p><b>Attempt 2</b></p>
<p>
  To try and hit the 75% goal, I increased the number of nodes were increased for the first and second layers to 100 and 45 respectively (Figure 2.1) for the second attempt.  The end result was an accuracy of 72.4% (Figure 2.2).
</p>

<p align=center>
  <img src='https://github.com/tc9993/neural-network-charity-analysis/blob/main/Resources/attempt3_define.GIF?raw=true' alt='Attempt 3 Defined'><br>
  <b>Figure 3.1:</b> Attempt 3 Defined
</p>
<p align=center>
  <img src='https://github.com/tc9993/neural-network-charity-analysis/blob/main/Resources/attempt3_outcome.GIF?raw=true' alt='Attempt 3 Outcome'><br>
  <b>Figure 3.2:</b> Attempt 3 Outcome
</p>
<p><b>Attempt 3</b></p>
<p>
  For attempt 3, a third hidden layer was added and contained 15 neurons (Figure 3.1).  Once again the accuracy registered at 72.4%, below the threshold (Figure 3.2).
</p>

<p align=center>
  <img src='https://github.com/tc9993/neural-network-charity-analysis/blob/main/Resources/attempt4_define.GIF?raw=true' alt='Attempt 4 Defined'><br>
  <b>Figure 4.1:</b> Attempt 4 Defined
</p>
<p align=center>
  <img src='https://github.com/tc9993/neural-network-charity-analysis/blob/main/Resources/attempt4_outcome.GIF?raw=true' alt='Attempt 4 Outcome'><br>
  <b>Figure 4.2:</b> Attempt 4 Outcome
</p>
<p><b>Attempt 4</b></p>
<p>
  For the fourth and final attempt, I upped the number of neurons in the second 2 of 3 hidden layers to 60 and 30 respectively, followed by adding a fourth layer with a Sigmoid activation (Figure 4.1).  This ended with an accuracy of 72.3%, once again below the 75% goal (Figure 4.2).
</p>

<h2>Summary</h2>

<h3>Overall Results</h3>

<h3>Recommendation</h3>
