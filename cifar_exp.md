### Full dataset

# CIFAR 10

Experiment 1
- INDIST : CIFAR 10 [30,000]
- OUTDIST : CIFAR 100 [20,000]

Experiment 2
- INDIST : CIFAR 10 [30,000]
- OUTDIST : CIFAR 100 [20,000] + CIFAR10 with SP noise 0.1 [1000]

Experiment 3
- INDIST : CIFAR 10 [30,000]
- OUTDIST : CIFAR 100 [20,000] + CIFAR100 with SP noise 0.1 [500]


SNo.| Data | Experts | Experiment | In Dist | Out Dist | Fast Sign | LBFGS | Deep Fool | Unsup |  Test FS | Test Usup |Log |
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | 
1 | CIFAR_10 | 21 | EXP1 | 67.52, 93.30, 86.98| 70.49, 92.75, 83.71| 57.73, 92.74, 88.05| 33.27, 88.75, 90.51 | 46.81, 90.97, 87.45 | 73.47, 94.31, 85.26 | 57.92, 92.78, 87.95| 74.73, 94.65, 85.13 | [full_exp1_cifar10_21](https://github.com/krishnakalyan3/Display/blob/master/log/full_exp1_cifar_21.txt)
2 | CIFAR_10 | 5 | EXP1 | 68.75, 89.92, 79.94 | 71.81, 84.95, 73.29 | 60.41, 85.94, 80.46| 40.21, 82.83, 83.56 | 53.51, 84.45, 79.82 | 79.89, 87.37, 72.57 | 60.87, 86.54, 80.59 | 80.18, 87.44, 72.46 |  [full_exp1_cifar10_5](https://github.com/krishnakalyan3/Display/blob/master/log/full_exp1_cifar_5.txt)
3 | CIFAR_10 | 21 | EXP2 | 67.27, 94.46, 89.25| 71.27, 94.11, 85.73| 58.73, 93.98, 88.88| 33.55, 90.45, 91.86 | 46.79, 92.32, 88.87 | 75.40, 95.31, 85.92 | 59.11, 94.00, 89.51 | 76.05, 95.44, 86.50 | [full_exp2_cifar10_21](https://github.com/krishnakalyan3/Display/blob/master/log/full_exp2_cifar_21.txt)
4 | CIFAR_10 | 5 | EXP2 | 69.10, 89.13, 78.63| 71.54, 83.43, 72.40| 60.80, 84.67, 79.13| 39.50, 81.97, 83.29| 54.58, 83.18, 79.36 | 80.70, 84.90, 71.55 | 61.39, 85.03, 79.41 | 80.21, 85.29, 71.18 | [full_exp2_cifar10_5](https://github.com/krishnakalyan3/Display/blob/master/log/full_exp2_cifar_5.txt)
5 | CIFAR_10 | 21 | EXP3 | 34.12, 92.71, 92.73 | 85.31, 96.75, 83.14| 64.02, 93.73, 87.12| 38.14, 90.07, 89.84| 53.10, 92.0, 86.60 | 79.90, 95.34, 85.13 | 63.91, 93.61, 87.17 | 79.84, 95.29, 84.99| [full_exp3_cifar10_21](https://github.com/krishnakalyan3/Display/blob/master/log/exp3_cifar21_v1.txt)
6 | CIFAR_10 | 5 | EXP3 | 39.69, 88.40, 87.64 | 82.71, 91.53, 73.03| 62.55, 86.75, 80.94| 40.73, 83.60, 84.18| 56.65, 85.20, 80.60 | 81.93, 87.89, 73.44 | 63.09, 87.21, 80.95 | 81.76, 88.02, 73.60| [full_exp3_cifar10_5](https://github.com/krishnakalyan3/Display/blob/master/log/exp3_cifar5_v1.txt)



