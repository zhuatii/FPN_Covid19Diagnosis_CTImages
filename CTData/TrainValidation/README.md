# Dataset Description

The dataset is sourced from the Kaggle dataset **"COVID-CTset: A Large COVID-19 CT Scans dataset"**, which is a smaller subset of the data used in the paper **"A fully automated deep learning-based network for detecting COVID-19 from a new and large lung CT scan dataset"** by Rahimzadeh et al. More details about the dataset can be found in the following GitHub repository: [COVID-CTset](https://github.com/mr7495/COVID-CTset).

Key Points:
- The dataset has undergone an image selection algorithm, which means scans with closed lungs have already been discarded.
- It is divided into 5 folds, each with its own training, validation, and test sets.
- The training set contains nearly equal numbers of normal and COVID-19 affected CT scans to ensure balanced learning.
- The validation and test sets have a higher proportion of normal images compared to COVID-19 affected scans.
