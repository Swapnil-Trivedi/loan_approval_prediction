# Loan Approval Prediction

Your Goal: The goal for this competition is to predict whether an applicant is approved for a loan.

## Evaluation

Submissions are evaluated using area under the ROC curve using the predicted probabilities and the ground truth targets.
 [ROC CURVE](http://en.wikipedia.org/wiki/Receiver_operating_characteristic)

 ### Submission file

 For each id row in the test set, you must predict target loan_status. The file should contain a header and have the following format:

 ```
id,loan_status
58645,0.5
58646,0.5
58647,0.5
etc.


 ```