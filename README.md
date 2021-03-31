# Sensors data

These data files accompany our paper "Quantification of gas concentrations in NOx/NH3/C3H8 mixtures using machine learning".

#### Training data:
concentrations_train.txt -> concentrations of the four gases in the training set. Column headings indicate gas type.

voltages_train.txt -> voltage response from the four sensors to the gases in 'concentrations_train.txt' file. Column headings indicate sensor type.

training_labels.txt -> label of data in the previous two training files. Each label corresponds to a gas mixture type.

#### Test data:
concentrations_test.txt -> concentrations of the four gases in the test set. Column headings indicate gas type.

voltages_test.txt -> voltage response from the four sensors to the gases in 'concentrations_test.txt' file. Column headings indicate sensor type.

test_labels.txt -> label of data in the previous two test data files. Each label corresponds to a gas mixture type.

The ordering of the data points in each of the concentrations, voltages and label files is the same i.e. the n'th line in each file describes concentration, voltage and label of one observation.


label_guide.txt -> matches label number to mixture type.
