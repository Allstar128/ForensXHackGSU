# ForensXHackGSU
## Inspiration
Nearly one billion people don't have access to clean, safe water. Some organizations are helping these people by installing water pumps for African villages, but funds and staff are often in short supply. We decided to analyze Tanzania's wells as a proof of concept for how this process can be made more efficient.

## What it does
Our project can take data in a standardized format to provide a comprehensive analysis of water pump performance. This includes visualization of the correlation between variables and real-time predictions of pump status using machine learning.

## How we built it
We delegated team roles and worked in Jupyter Notebook to create our graphs and machine learning models. The different models were tested against each other with various parameters to evaluate their performance. We chose the most relevant data and the best model and created a dashboard using a dash which allows the creation of a front end with HTML, CSS, and Python.

## Challenges we ran into
1. Dash - Because our team's focus is the machine learning backend, our weakness is the front end. We had to spend a lot of time to make the dashboard look good and be functional
2. Machine Learning Model - Our machine learning model was initially receiving very low prediction accuracy. After doing some research, testing different models, and working more with hyperparameters and data engineering we were able to create a Machine Learning model with a high prediction accuracy
3. Data Engineering - When working on a Machine Learning project, it is often required to perform some sort of data engineering in order to create a viable machine learning model. One form of engineering that we utilized was Label Encoding. We struggled with creating an entire new dataframe with the encoded value and its corresponding label.

## Accomplishments that we're proud of
1. Machine Learning Model - We are very proud of our machine learning model as it has a high prediction accuracy and enables us to predict status of wells as a function of time
2. Dash - Our Dash App is well organized and interactive. We are inexperienced with dash, so we are pleased with the result of our efforts.

## What we learned
1. Dash - We learned how to make a more complex and interactive Dash App
2. Machine Learning - We learned how to evaluate our machine learning models to select the best one
3. Data Visualizations - We learned how to create more complex data visualizations

## What's next for Water Well Analytics and Forecasting in Africa
Water Wells Analytics and Forecasting in Africa is a proof of concept. Data from any location can be used as long as it is in the same format, which makes our application very versatile. We will improve the app by making a more general and interactive UI interface in which the AI can be utilized with ease to generate results and predictions for the user.
