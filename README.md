Calculate the double threshold of the maximum entropy of the remote sensing image to be segmented, and use cuckoo optimization.
This code is a batch calculation script
In this code:
1. read TIFF images
2. Calculating the TSVD and got multiple components
3. Compute double thresholds for the first component based on maximum entropy
4. Use cuckoo search to get the best result

Notice:
1. The following error is reported, you can increase the number of iterations
2. Adjust the number of decimal places after floating point numbers to control threshold accuracy and calculation amount
