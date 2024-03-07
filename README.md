<h1>Twitter Sentiment Analysis with Linear Regression</h1>

<p>This project aims to perform sentiment analysis on a dataset of 1,600,000 tweets using linear regression. The goal is to predict the sentiment (positive or negative) of tweets based on their content.</p>

<h2>Dataset</h2>

<p>The dataset used in this project consists of 1.6 million tweets collected from Kaggle dataset. Each tweet is labeled with its sentiment (positive or negative).</p>
<p>You can use it's mini version from the repository <code>twitter-data-preprocessed</code></p>

<h2>Preprocessing</h2>

<p>Before training the linear regression model, the data underwent preprocessing to clean and prepare it for analysis. The preprocessing steps include:</p>
<ol>
    <li><strong>Stemming</strong>: The tweets were processed using stemming to reduce each word to its root form. This helps in reducing the dimensionality of the data and improving model performance.</li>
</ol>

<h2>Training the Model</h2>

<p>After preprocessing the data, a linear regression model was trained using the preprocessed tweets as input features and their corresponding sentiment labels as targets.</p>

<h2>Evaluation</h2>

<p>The performance of the linear regression model was evaluated using various metrics such as accuracy, precision, recall, and F1-score.</p>

<h2>Future Work</h2>

<p>In future iterations of this project, additional techniques such as CNN, RNN, feature engineering, hyperparameter tuning, and using more advanced machine learning algorithms could be explored to improve the model's performance further.</p>

<h2>How to Use</h2>

<p>To replicate the results of this project, follow these steps:</p>
<ol>
    <li>Clone this repository to your local machine.</li>
    <li>Install the required dependencies listed in the <code>requirements.txt</code> file.</li>
    <li>Download the dataset (link to dataset) and place it in the <code>data</code> directory.</li>
    <li>use the preprocessed csv file (<code>preprocess.py</code>) to get rid of cleaning and preprocessing the data to wait for long time.</li>
    <li>Train the linear regression model using the preprocessed data or you can use <code>trained-model-twitter-sentiment.sav</code></li>
    <li>Evaluate the model's performance and analyze the results.</li>
</ol>

<h2>Dependencies</h2>

<ul>
    <li>Python 3.x</li>
    <li>scikit-learn</li>
    <li>nltk</li>
</ul>

<h2>Contributors</h2>

<ul>
    <li>Rahul Kumar (@rahulkumarroy477)</li>
</ul>

