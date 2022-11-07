# Network Anomaly Detection 
This network anomaly detection system creates a model to detect networks attacks belonging to 4 known attack (output) classes: Denial of Service (DoS), Probe, User to Root (U2R) and Local to Remote (L2R). The model is trained using a randomized 80/20 split on the combination of the KDDTrain+ and KDDTest+ datasets.

# Set Up
System setup includes requires installing the required dependencies.
A list of all required dependencies can be found in `Requirements.txt`

## Place Datasets in Folder
The following NSL-KDD datasets must be placed in `Datasets/`:

KDDTrain+.ARFF    |    KDDTrain+.TXT
KDDTest+.ARFF     |     KDDTest+.TXT

The NSLKDD dataset can be downloaded [here](https://www.unb.ca/cic/datasets/nsl.html)