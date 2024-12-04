# Encoding
Encoding is the process of converting data from one form to another.
-Categorical features are generally divided into 3 types
  - Binary
  - Ordinal
  - Nominal
    
## Label encoding refers to converting the labels into numeric form so as to convert it into the machine-readable form.
- The values are assigned accordingly in ascending alphabetical order.

## One Hot Encoding
- Datasets might contain columns that has no specific order of preferance.
- Label encoding such data may mislead the algorithm.
- The data in the column usually contains categorical value which is then converted to machine readable form.

Human-Readable                  Machine-Readable

  Pet                          Cat    Dog    Turtle   Fish
  Cat                          1       0        0      0
  Dog                          0       1        0      0
  Turtle                       0       0        1      0
  Fish                         0       0        0      1
  Cat                          1       0        0      0


# Target Encoding
Each category in a categorical variable is replaced with a statistical summary of the target variable.

# Frequency Encoding
Each category in a category variable is replaced with the frequency or count of that category in the dataset.
-Where to apply:
  - High Cardinality categorical values
  - Unsupervised learning tasks
  - Features where the frequency of a category carries important information.

# Feature scaling
It is a technique to standardize the independent features present in the data in afixed range.
- Performed during the data preprocessing to handle highly varying magnitudes or values or unts.
- If feature scaling is not done , then a machine learning algorithm tends to weigh greater values.
- 2 types
   - Min max scaler
   - Standard scaler
 
# Standard Scaling
Rescales s feature value so that it has distribution with 0 mean value and variance equals to 1.
- It follows standard normal distribution(SND)
- The equation of standard scaler is
  ![https://miro.medium.com/v2/resize:fit:932/0*WrXe0uhKc-Yb4H8G.jpg]


# Min max scaling
Re scales a feature or observation value with distribution value between 0 and 1
- The equation of min max scaler is
- 

