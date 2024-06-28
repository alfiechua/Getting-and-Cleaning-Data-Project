# Code Book

## Variables

- `subject`: ID of the subject
- `activity`: Activity performed by the subject

The following variables represent the mean and standard deviation measurements:

- `TimeBodyAccelerometerMeanX`
- `TimeBodyAccelerometerMeanY`
- `TimeBodyAccelerometerMeanZ`
- `TimeBodyAccelerometerStdX`
- `TimeBodyAccelerometerStdY`
- `TimeBodyAccelerometerStdZ`
- ...

## Transformations

1. Merged the training and test datasets.
2. Extracted measurements on the mean and standard deviation.
3. Used descriptive activity names.
4. Labeled the dataset with descriptive variable names.
5. Created a second, independent tidy data set with the average of each variable for each activity and each subject.
