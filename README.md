# Cross Validation

Cross Validation | Example code and own notes while taking the course "Intro to Machine Learning" on Udacity.

## Training, Transforms, Predicting

![flow](resources/flow.png)
![test-train](resources/test-train.png)

## Problems with splitting into training & testing data
![normal-split](resources/normal-split.png)

### K-fold
![k-fold](resources/k-fold.png)

Run K seperate learning experiments
- Pick testing set
- Train
- Test only testing set

⭐️Average test results from those K experiments.
