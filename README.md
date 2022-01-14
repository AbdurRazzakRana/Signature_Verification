# Signature Verification

Prerequisite: 
Tensorflow installed.
Anaconda installed.
CV2 installed.
Numpy installed.
Data set.

Process of working:
1. You will collect signatures from persons, such as signatures from two person A, B.
2. Create directories named A and B and put the respective signature.
3. Separate 20% of the signatures randomely to test including some fruad signature.
4. After running the SystemTraining.py file for an enough time, It will generate some files of learning.
5. predictAll.py file will predict all the signatures including accuracy. Lower the accuracy of the same person's signature higher the chance of fraudulent signature.
