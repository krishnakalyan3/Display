### CIFAR 10

Experiment 1
- INDIST : CIFAR 10 [30,000]
- OUTDIST : CIFAR 100 [20,000]

Experiment 2
- INDIST : CIFAR 10 [30,000]
- OUTDIST : CIFAR 100 [20,000] + CIFAR10 with SP noise 0.1 [1000]

Experiment 3
- INDIST : CIFAR 10 [30,000]
- OUTDIST : CIFAR 100 [20,000] + CIFAR100 with SP noise 0.1 [1000]


SNo.| Data | Experts | Experiment | In Dist | Out Dist | Fast Sign | LBFGS | Deep Fool | Unsup |  Test FS | Test Usup |Log |
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | 
1 | CIFAR_10 | 21 | EXP1 | 67.82, 93.20, 86.44| 70.59, 92.54, 82.98 | 58.49, 92.17, 87.01| 33.56, 88.38, 89.75 | 46.40, 89.99, 86.79 | 76.66, 93.84, 83.02| 57.96, 92.19, 86.83| 75.51, 94.40, 83.43 | [exp1_cifar10_21](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/exp1_cifar_21.txt)
2 | CIFAR_10 | 5 | EXP1 | 64.34, 87.09, 80.80 | 80.00, 86.68, 71.29 | 67.85, 87.37, 78.29 | 47.23, 83.87, 80.99 | 61.62, 85.23, 77.86 | 86.83, 89.45, 71.22 | 68.04, 87.70, 78.17 | 86.71, 89.78, 70.85 |  [exp1_cifar10_5](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/exp1_cifar_5.txt)
3 | CIFAR_10 | 21 | EXP2 | 63.92, 93.39, 89.21| 81.75, 95.96, 84.15| 64.55, 93.86, 87.27| 40.07, 90.00, 90.69| 52.79, 91.79, 87.20| 81.00, 95.65, 85.56 | 64.65, 94.01, 87.77| 80.95, 95.83, 85.38| [exp2_cifar10_21*](https://github.com/krishnakalyan3/Display/blob/master/log/exp2_cifar_21_v2.txt)
4 | CIFAR_10 | 5 | EXP2 | 65.04, 87.84, 81.08| 81.40, 88.39, 71.43| 70.10, 87.56, 78.34| 47.10, 83.68, 81.27| 63.73, 85.63, 77.31| 88.70, 89.50, 69.93 | 70.29, 88.04, 78.22| 89.08, 89.55, 70.13| [exp2_cifar10_5*](https://github.com/krishnakalyan3/Display/blob/master/log/exp2_cifar_5_v2.txt)
6 | CIFAR_10 | 21 | EXP3 | 63.76, 91.86, 88.67 | 86.04, 96.59, 83.71| 67.59, 93.80, 87.34| 41.75, 89.44, 89.36| 56.49, 91.43, 85.87 | 83.20, 95.99, 85.37 | 67.19, 94.10, 87.33 | 82.85, 96.04, 85.14| [exp3_cifar10_90_epoch*](https://github.com/krishnakalyan3/Display/blob/master/log/exp3_cifar_21_v2.txt)
6 | CIFAR_10 | 5 | EXP3 | 66.38, 87.58, 80.87 | 81.43, 87.81, 69.39| 66.63, 87.15, 77.94| 44.28, 83.86, 81.42| 59.45, 85.30, 77.30 | 86.10, 88.49, 70.19 | 66.47, 87.67, 77.70 | 86.16, 88.77, 69.51| [exp3_cifar10_5](https://github.com/krishnakalyan3/Display/blob/master/log/exp3_cifar10_5_v2.txt)
