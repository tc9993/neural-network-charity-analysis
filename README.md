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

<h2>Summary</h2>

<h3>Overall Results</h3>

<h3>Recommendation</h3>
