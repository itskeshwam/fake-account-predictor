# Twitter Fake Account Detector
This project is a graphical user interface (GUI) application for detecting fake Twitter accounts using machine learning models. The application is built using Python with the tkinter library for the GUI and machine learning algorithms such as Naive Bayes, Linear SVC, and K-Nearest Neighbors for classification.

## Features
1. Load Twitter Data:

    * Browse and load a CSV file containing Twitter account data.
2. Classifiers:

    * Use one of the three classifiers to predict whether an account is fake:
    * Naive Bayes
    * Linear SVC
    * K-Nearest Neighbors (KNN)

3. Manual Input:
    * Manually input account details for prediction.
4. Comparison of Classifiers:
    * Compare the accuracy and error rates of all three classifiers using bar plots.

5. Visualization:

    * Display performance metrics such as accuracy, error rate, precision, and recall.
    * Pie charts for individual classifier performance.
    * A combined bar chart for comparing classifiers.

## Prerequisites
1. Python: Ensure Python 3.8 or later is installed.
2. Libraries: Install the following libraries:
    * numpy
    * pandas
    * matplotlib
    * scikit-learn
    * tkinter (built into Python)

Install these libraries using:

```bash
pip install numpy pandas matplotlib scikit-learn
```
## Running the Application
1. Save the script to a file, e.g., fake_account_detector.py.
2. Run the script using:
```bash
python fake_account_detector.py
```
3. The application window will open.

## Using the Application
### Step 1: Load Data
1. Click the "Browse File" button.

2. Select a CSV file containing Twitter account data.

### Step 2: Run Classifiers
* Click one of the classifier buttons (e.g., Naive Bayes, Linear SVC, or KNN).
* View performance metrics and a pie chart for the selected classifier.
### Step 3: Provide Manual Input (Optional)
1. Click "Give Manual Input".
2. Fill in the required fields for a Twitter account.
3. Choose a classifier to predict the account type.
### Step 4: Compare Classifiers
* After running all three classifiers, click "Compare".
* A bar chart will display the accuracy and error rates of all classifiers.

## Key Functions
1. browse():
    * Allows the user to select the input data file.

2. Naive_Bayes(), Linear_Svc(), Knn():
    * Train and test respective classifiers, display metrics, and plot results.

3. Create_Input_Window():
    * Opens a new window for manual input.

4. compare():
    * Compares the performance of all classifiers.

## Notes
1. Data Requirements:

    * Ensure the CSV file has consistent formatting and numeric data.
    * Missing or invalid data may result in errors.

2. Classifier Training:
    * Training data is split randomly (70% training, 30% testing).

3. Dependencies:
    * Ensure all required libraries are installed.

4. Performance Metrics:
    * Metrics include accuracy, error rate, precision, and recall.

## Future Improvements
  1. Support for additional classifiers.
  2. Enhanced error handling for missing or invalid data.
  3. Save and load classifier models.

## License
This project is provided "as-is" without any guarantees. Users are responsible for any consequences of using this application.

Enjoy detecting fake Twitter accounts with machine learning! 😊
