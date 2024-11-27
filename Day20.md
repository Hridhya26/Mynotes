## Datatypes
- continuous - Eg : temperature
- discrete - can only be expressed as whole numbers and can be counted.
- classification and regression - Classification and regression are both supervised machine learning algorithms that find patterns in data to predict outcomes. The main difference between the two is that classification predicts discrete categories, while regression predicts continuous numerical values.

- Classification and regression model.
  
## Numerical and categorical varible
- Numerical again divided into continuous and discrete.
- The main difference between numerical and categorical variables is that numerical variables are quantifiable and represent numbers, while categorical variables are non-numerical and represent groups

## Visualization
- Matplotlib
          - Figures
          - Axis labels
          - Sub-figures
          - Ticks

## Types of plots
   - Line plot
   - Bar charts
   - Pie Charts
   - Histogram
   - CDF plot
   - KDE plot
   - Scatter plot
      - with colour
   - Heatmaps
   - Box plots
- Seaborn

## Feature Extraction and Transformation
Feature extraction
This process reduces the complexity of data while keeping as much relevant information as possible. It can involve creating new features or manipulating data to separate meaningful features from irrelevant ones. Feature extraction can be done manually or automatically. 

Feature transformation
This process involves modifying existing features in a dataset to better suit the model training. Techniques like log normalization, standard scaling, and encoding are used for this. 


## Features and Labels 
features are the variables or attributes that a model uses to make predictions, while labels are the outcomes or answers that the model predicts.

## Featurization 
- Featurization, also known as feature engineering, is the process of transforming data into a format that can be used as input for a machine learning (ML) model: 
   - Text data
      - BoW - Bag of Words (BoW): A featurization technique for textual data
      - TFIDF - A featurization technique for textual data 

## Feature Engineering
- Feature Orthogonality - can be checked using Pearson correlation coefficient.
- Cosine Similarity - u.v/|u||v| , if orthogonal ie u.v is zero,then cosine similarity is zero.
- Feature Colinearity - if f2 = 1.5f1 or a multiple of f1,then f1 f2 are said to be colinear. This is not preferred.
- Feature Slicing - Feature-sliced design (FSD) is an architectural methodology for organizing code in front-end applications. It involves dividing a product's features into independent components, or "slices", which are then designed and developed separately. 
- Indicator Variable - An indicator variable is a variable that can only have two values, 0 and 1, and is used to represent the presence or absence of an attribute. They are also known as dummy variables. 
- Feature Binning - Feature binning is a technique that groups numerical data into bins or buckets to create categorical data. It is also known as bucketing.
- Mathematical Transforms
   - Logarithms
   - FFT & STFT 

- Logarithms - Used in the CWT spectrograms, which have an equal resolution on a log-frequency scale. 

- FFT - A computationally efficient algorithm that computes the Discrete Fourier Transform (DFT) of a sequence. The FFT is based on a "divide and conquer" algorithm that reduces the number of numerical operations required to compute the DFT. The FFT is used for signal filtering, spectral estimation, and data compression.

- STFT - A variation of the FFT that allows for simultaneous analysis in time and frequency domains. The STFT spectrograms have an equal resolution on a linear frequency scale.
