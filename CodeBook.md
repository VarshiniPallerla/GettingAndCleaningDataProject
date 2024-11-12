# CodeBook for Human Activity Recognition Using Smartphones Dataset

This code book describes the variables and the transformations that were applied in the `run_analysis.R` script.

## Data

- The dataset contains measurements from accelerometers from Samsung Galaxy S smartphones.
- It includes 561 feature measurements and activity labels.

## Variables

- `subject`: The ID of the subject (1-30).
- `activity`: The name of the activity (e.g., Walking, Sitting).
- Variables containing `mean()` and `std()` refer to mean and standard deviation measurements.

## Steps to Clean the Data

1. Merged the training and test datasets.
2. Extracted only mean and standard deviation measurements.
3. Used descriptive names for activities.
4. Labeled the dataset with descriptive variable names.
5. Created a tidy dataset with the average of each variable for each activity and subject.
