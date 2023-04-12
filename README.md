# Used Car Data Analysis for 2021
This project involves the analysis of a dataset containing information on used car sales in the United States. The data was scraped from Craigslist every few months, and includes columns such as price, condition, manufacturer, latitude/longitude, and 18 other categories.

## Data Source
The dataset was obtained from Kaggle (https://www.kaggle.com/austinreese/craigslist-carstrucks-data) and contains over 500,000 observations from various cities in the United States.

## Analysis
The analysis of the dataset includes several key components, such as:

- Data cleaning: removing any duplicates, missing values, or outliers from the dataset to ensure accuracy and consistency in the analysis.

- Exploratory data analysis (EDA): performing basic statistical analyses to explore the relationships between the different variables in the dataset.

- Visualization: creating various plots and charts to visualize the trends and patterns discovered in the data.

- Regression analysis: using linear regression models to predict the prices of used cars based on different variables such as the car's age, condition, and mileage.

## Technologies Used
The analysis was performed using Python and several Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

## Repository Contents
- raw_data/ - contains the original dataset used for the analysis

- Used_Cars_Analysis/ - contains Jupyter notebooks used for data cleaning, EDA, visualization, and regression analysis

- cleaned_used_car_data/ - contains a cleaned and newer version of raw data

## Key Findings
The most common manufacturers of used cars sold on Craigslist are Ford, Chevrolet, and Toyota.

There is a strong negative correlation between a car's age and its price, meaning that older cars tend to be less expensive.

The price of used cars tends to increase as their mileage decreases, indicating that lower mileage is a key factor in determining the value of a used car.

# Tableau Viz
<div class='tableauPlaceholder' id='viz1681323834477' style='position: relative'><noscript><a href='#'><img alt='Overview ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CW&#47;CW3B6HDST&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;CW3B6HDST' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CW&#47;CW3B6HDST&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1681323834477');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1427px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

# Conclusion
This analysis provides valuable insights into the used car market in the United States and can be used to inform purchasing decisions or guide future research. 
By using Python and various Python libraries, we were able to effectively clean, analyze, and visualize the data to uncover important trends and patterns in the dataset.





