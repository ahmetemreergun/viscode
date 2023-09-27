To automate the maincode.ipynb to run with different scenarios,

# Parameters
strategies = ['0','1'] #1 for Padding, 0 for Differential Privacy (FPA)

pads = ['100', '300', '350', '500', '700', '900', '1000', '1500'] #level 100, level 300, level 350, level 500, level 700, level 900, random, MTU

vectors = ['50', '40', '30', '25', '20', '15', '10', '5'] #Vector Size: 5, 10, 15, 20, 25, 30, 40, 50

ks = ['10', '20'] #coefficients: 10, 20 

epsilons = ['0.05', '0.5', '5', '10'] #epsilon: 0.05, 0.5, 5, 10

code part in outputscode.ipynb contains parameters for different scenarios.

Running outputscode.ipynb runs maincode.ipynb code file untill all combinations are done and saves output html files in folder.

dayss.csv file contains train dataset (https://drive.google.com/file/d/13_2atu3jJHvrYKtIhYy9E-mElnldaVmW/view?usp=sharing)

nextweekday2.csv file contains test dataset
