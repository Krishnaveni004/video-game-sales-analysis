![Image](http://oyster.ignimgs.com/wordpress/stg.ign.com/2012/10/Angry-Birds-Trilogy-Graphical-Header-for-Review.jpg)
## Project idea: Video Game Sales Analysis and  Prediction
I will be using Kaggle data available [here](https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings) to analyze and predict the ratings of video games based on 16 features. The dataset has 16,719 records, hence I will be using pandas and other visualization libraries to analyze the dataset and predict using Machine Learning models available through scientific libraries like scikit-learn, etc.

Tasks in the project:
- Data pre-processing
- Visualization to understand the data patterns
- Learn about different Machine Learning models used for the data pattern observed in Step 2
- Model building
- Evaluation of the performance of the built Model
- Results report

What can I Learn?
- pandas, NumPy, etc.
- Data processing technologies
- Visualization through libraries like matplotlib etc.
- About prediction techniques

## Project Execution Plan
### Week 4: Planning and Data Collection
Target: By end of Week 4, I will have completed data gathering and collecting information about important steps in data analysis, tools used, packages used, etc. from different blogs and articles on the net

### Week 5: Data Inspection and Pre-processing
Target: By the end of Week 5, I would be completing the data preprocessing and data inspection portion of my Data Analysis project.

**“GARBAGE IN, GARBAGE OUT”**

Planned steps:

After reading different articles and blogs about pre-processing in data analysis projects, I have found the following steps crucial. It is been shown that “45% of a data scientist’s time is spent on data preparation tasks” - Datanami
- Data cleaning
  - Checking for missing values
  - Categorical v/s Numerical Data
  - Splitting Data into Training and Test datasets
  - Feature Scaling 
- Data integration
  - In my project, this step is ignored, as my dataset is aggregated already by Kaggle
- Data reduction
  - Attribute selection
  - Numerosity reduction
  - Dimensionality reduction
- Data transformation
  - Aggregation
  - Normalization
  - Feature selection
  - Discreditization

### Week 6: Visualization and Understanding Features
Target: By the end of Week 6, I will have done data visualization on my dataset and tried to understand the correlation between different features at my disposal. This would enable feature selection

**“Data visualization is the language of decision making”**

Planned steps:

- To analyze data in a chronological sense (by year)
  - Questions to answer:
    - How is the trend of video games over a period of time
    - Is the trend common across different geographical locations
- To visualize the prominence of Branding in video games (by publisher)
  - Questions to answer:
    - Who are the prominent players
    - How does Brand affect the ratings of video-games
- To visualize based on Genre and platform 
  - Questions to answer:
    - Which genre dominates the industry
    - How many games are released in those genres
    - Does the platform play a role? PS2 vs PS4

### Week 7: Learning and Experimentation
Target: To study different models used for the data patterns observed and experiment with those models on my dataset. Also, look for implementation tools, Google Colab?

Planned tasks:
- Implement different models
- Compare results
- Regression v/s Classification (Need to read more about it)

### Week 8: Hyper-parameter Tuning
Target: Every model can be tuned to use certain parameters which affect model performance

**“THE BRAIN of THE MODEL”**

Planned tasks:

- Optimize performance through parameter tuning
- Interpret results
- What does the pattern convey? Can a prediction be made?
- How accurate is the model?

### Week 9:
Planned tasks:
- Make a video for submission
- Prepare a report of the results

## Results:

Dataset: [Kaggle](https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings)

**Video Link:** [Panopto](https://pro.panopto.com/Panopto/Pages/Viewer.aspx?tid=68ff4e6b-f400-4f56-b773-af6300230b43&start=0)

**How to run project?** Install requirements specified in requirements.txt and run using jupyter

In case of numeric_only=True error, it is due to different version of pandas. Please use requirements.txt to install requirements. Alternatively, please remove numeric_only=True parameter.