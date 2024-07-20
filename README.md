# Youtube-toxic-comments-classification

Data Import: The dataset containing the video IDs and comments was imported from Kaggle.

Text Preprocessing: The data was preprocessed by removing stop words, removing unwanted special characters etc. Then the text data was converted to features which can be passed to the model using Tfidf Vectoriser. The imbalance in the dataset was managed through SMOTE.

Data Visualization: Created box plots, pie charts, co-occurrence matrix and word clouds to explore data characteristics.

Model Building: This model implements neural networks to classify the comments as toxic or non-toxic

Evaluation: Achieved a 81% accuracy and 100% on SVM.
