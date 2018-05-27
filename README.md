# Hackathon_FraudDetector
Fraud Detector in Insurance Claims



Assumptions:

We have made the following assumptions to achieve the required result
	*We have considered only required fields mentioned in the dataset for the detection of fraud and non-fraud claims
	*The fields like GroupId, Amount, Days in hospital, Emergency indicator, etc.,
	*Based on these fields we have applied logic that for a type of group id there can be few limitations when that gets exceded it becomes a fraud claim.
	*Both trained data and test data are available within the project itself.

Note: Don't change the traindata and testdata csv files' path.


Please read Installationdoc.doc to install the required softwares in your computer.


Steps to run the program:

   1. Open testdata.csv and give your input. Last column is what the program is going to predict. For now, give good/bad. Minimum one good and one bad input.
   2. You can feed as many data as you like to the testdata.
   3. Open Eclipse IDE and import the project as Java Project.
   4. Run FraudDetectorImpl.java
   5. Predictions will be displayed in the console screen.
