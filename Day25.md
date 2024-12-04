# Encoding
-Encoding is the process of converting data from one form to another.
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
