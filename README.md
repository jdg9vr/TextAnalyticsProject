# TextAnalyticsProject

This is my Text Analytics Project for DS 5001 Spring 2023. I would like to acknowledge help from Rachel Treene as well as Hyun Ko in creating this project, though the deliverables and final report are completely my own. This project analyzes company website text data from my Capstone Project. My final report is called FINAL_REPORT.ipynb and is accessible [here](FINAL_REPORT.ipynb)

## Files

### ```Anonymizer.ipynb```

This notebook anonymizes the company information from my Capstone data. We were requested by our Capstone client to anonymize the data "just in case" so that is what this notebook does.

### ```Correlation.ipynb```

This notebook provides my exploration of correlation between the companies. I create my KDE plots in this notebook for use in my final notebook

### ```Create_subset.ipynb```

This notebook creates a subset from the full English data that we use in the Capstone project. This file is used with the Anonymzer to create the final corpus that is used in this project

### ```FINAL_REPORT.ipynb```

This notebook is my final report for this project. This contains the beef and outward facing text for my analysis and my takeaways from this project. It is split up into sections: Introduction, Source Data, Data Model, Exploration, Interpretation. This report contains a data model, which more fully breakdowns all the datasets in the data folder.

### ```LDA.ipynb```

This notebook contains my LDA analysis and exploration, of which I included the topic histogram in the final report.

### ```main.ipynb```

This notebook is where I created all the core tables. This is also where I began exploration of all my other models. This was the first notebook in which I began analysis for this project, after the data was ready.

### ```PCA.ipynb```

This notebook contains my exploration and modeling of PCA on my data. It contains the loadings visualization and the PC visualizations, both of which I use in my final report.

### ```Sentiment.ipynb```

This notebook is where I performed my sentiment analysis, of which I included the emotion tables in my final report.

### ```Word2Vec.ipynb```

I performed my Word2Vec word embeddings of my data in this notebook. While I explored other aspects of this model, I ended up including both similes as well as the visualization of the word vectors in 2-dimensional space for my final report.