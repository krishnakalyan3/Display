### Meta Classifier Results

<<<<<<< HEAD
=======
# MNIST
SNo.| Data | Experts | Experiment |In Dist | Out Dist| Fast Sign | LBFGS | Deep Fool | Unsup | Log |
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
1 | MNIST | 21 | EXP1 | 99.16, 99.93, 87.84| 98.62, 99.81, 93.41 | 36.09, 95.38, 96.38 | 19.16, 90.93, 96.79 | 27.482, 93.41, 95.74 | 52.96, 94.92, 94.28 | [exp1_mnist_21](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/exp1_mnist_21.txt)
2 | MNIST | 5 | EXP1 | 98.69, 95.85, 86.20| 89.12, 98.17, 80.73| 47.00, 94.47, 93.38| 48.62, 88.91, 90.50 | 45.84, 91.70, 92.37 | 69.35, 95.88, 91.34| [exp1_mnist_5](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/exp1_mnist_5.txt)
3 | MNIST | 21 | EXP2 | 98.70, 99.57, 85.44| 98.71, 99.82, 90.26| 76.51, 95.20, 87.96| 23.05, 88.87, 94.89 | 54.66, 94.69, 91.27| 90.30, 93.64, 78.65| [exp2_mnist_21](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/exp2_mnist_21.txt)
4 | MNIST | 5 | EXP2 | 98.56, 97.23, 88.26| 88.35, 98.07, 85.72| 57.52, 94.75, 90.39| 57.15, 89.12, 85.25 | 57.66, 92.77, 86.15| 79.60, 95.75, 82.18| [exp2_mnist_5](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/exp2_mnist_5.txt)
>>>>>>> 59ac7315df6721dad9f3a5a9f24de2484c4cf73d

# CIFAR 10

Experiment 1
- INDIST : CIFAR 10 [30,000]
- OUTDIST : CIFAR 100 [20,000]

Experiment 2
- INDIST : CIFAR 10 [30,000]
- OUTDIST : CIFAR 100 [20,000] + CIFAR10 with SP noise 0.1 [1000]

<<<<<<< HEAD
# Experiment 3
- INDIST : CIFAR 10 [30,000]
- OUTDIST : CIFAR 100 [20,000] + CIFAR100 with SP noise 0.1 [500]

=======
>>>>>>> 59ac7315df6721dad9f3a5a9f24de2484c4cf73d
### Observed Accuracies

Sequence

- Accuracy
- Average Correct Confidence
- Average Incorrect Confidence

SNo.| Data | Experts | Experiment | In Dist | Out Dist | Fast Sign | LBFGS | Deep Fool | Unsup |  Test FS | Test Usup |Log |
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | 
1 | CIFAR_10 | 21 | EXP1 | 67.82, 93.20, 86.44| 70.59, 92.54, 82.98 | 58.49, 92.17, 87.01| 33.56, 88.38, 89.75 | 46.40, 89.99, 86.79 | 76.66, 93.84, 83.02| 57.96, 92.19, 86.83| 75.51, 94.40, 83.43 | [exp1_cifar10_21](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/exp1_cifar_21.txt)
2 | CIFAR_10 | 5 | EXP1 | 64.34, 87.09, 80.80 | 80.00, 86.68, 71.29 | 67.85, 87.37, 78.29 | 47.23, 83.87, 80.99 | 61.62, 85.23, 77.86 | 86.83, 89.45, 71.22 | 68.04, 87.70, 78.17 | 86.71, 89.78, 70.85 |  [exp1_cifar10_5](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/exp1_cifar_5.txt)
3 | CIFAR_10 | 21 | EXP2 | 72.08, 95.62, 84.54| 86.05, 96.31, 82.60| 82.47, 94.74, 82.51| 69.56, 93.01, 85.89| 74.66, 92.82, 83.03| 89.90, 97.75, 84.52 | 82.41, 94.38, 82.89| 89.09, 97.64, 84.24| [exp2_cifar10_21](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/exp2_cifar_21.txt)
4 | CIFAR_10 | 5 | EXP2 | 67.89, 83.87, 60.88| 76.77, 77.90, 70.93| 65.15, 77.77, 75.65| 47.94, 73.99, 79.17| 58.59, 75.88, 75.58| 84.39, 80.79, 72.06 | 64.47, 77.94, 75.76| 83.75, 80.81, 71.67| [exp2_cifar10_5](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/exp2_cifar_5.txt)
<<<<<<< HEAD
5 | CIFAR_10 | 5 | EXP3 

=======

[aux_cifar_exp2_5](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/aux_exp2_cifar_5.txt)
[aux_cifar_exp2_21](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/aux_exp2_cifar_21.txt)
>>>>>>> 59ac7315df6721dad9f3a5a9f24de2484c4cf73d

### Full dataset

SNo.| Data | Experts | Experiment | In Dist | Out Dist | Fast Sign | LBFGS | Deep Fool | Unsup |  Test FS | Test Usup |Log |
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | 
1 | CIFAR_10 | 21 | EXP1 | 67.52, 93.30, 86.98| 70.49, 92.75, 83.71| 57.73, 92.74, 88.05| 33.27, 88.75, 90.51 | 46.81, 90.97, 87.45 | 73.47, 94.31, 85.26 | 57.92, 92.78, 87.95| 74.73, 94.65, 85.13 | [full_exp1_cifar10_21](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/full_exp1_cifar_21.txt)
2 | CIFAR_10 | 5 | EXP1 | 68.75, 89.92, 79.94 | 71.81, 84.95, 73.29 | 60.41, 85.94, 80.46| 40.21, 82.83, 83.56 | 53.51, 84.45, 79.82 | 79.89, 87.37, 72.57 | 60.87, 86.54, 80.59 | 80.18, 87.44, 72.46 |  [full_exp1_cifar10_5](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/full_exp1_cifar_5.txt)
3 | CIFAR_10 | 21 | EXP2 | 67.27, 94.46, 89.25| 71.27, 94.11, 85.73| 58.73, 93.98, 88.88| 33.55, 90.45, 91.86 | 46.79, 92.32, 88.87 | 75.40, 95.31, 85.92 | 59.11, 94.00, 89.51 | 76.05, 95.44, 86.50 | [full_exp2_cifar10_21](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/full_exp2_cifar_21.txt)
4 | CIFAR_10 | 5 | EXP2 | 69.10, 89.13, 78.63| 71.54, 83.43, 72.40| 60.80, 84.67, 79.13| 39.50, 81.97, 83.29| 54.58, 83.18, 79.36 | 80.70, 84.90, 71.55 | 61.39, 85.03, 79.41 | 80.21, 85.29, 71.18 | [full_exp2_cifar10_5](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/full_exp2_cifar_5.txt)


<<<<<<< HEAD
# MNIST
SNo.| Data | Experts | Experiment |In Dist | Out Dist| Fast Sign | LBFGS | Deep Fool | Unsup | Log |
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
1 | MNIST | 21 | EXP1 | 99.16, 99.93, 87.84| 98.62, 99.81, 93.41 | 36.09, 95.38, 96.38 | 19.16, 90.93, 96.79 | 27.482, 93.41, 95.74 | 52.96, 94.92, 94.28 | [exp1_mnist_21](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/exp1_mnist_21.txt)
2 | MNIST | 5 | EXP1 | 98.69, 95.85, 86.20| 89.12, 98.17, 80.73| 47.00, 94.47, 93.38| 48.62, 88.91, 90.50 | 45.84, 91.70, 92.37 | 69.35, 95.88, 91.34| [exp1_mnist_5](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/exp1_mnist_5.txt)
3 | MNIST | 21 | EXP2 | 98.70, 99.57, 85.44| 98.71, 99.82, 90.26| 76.51, 95.20, 87.96| 23.05, 88.87, 94.89 | 54.66, 94.69, 91.27| 90.30, 93.64, 78.65| [exp2_mnist_21](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/exp2_mnist_21.txt)
4 | MNIST | 5 | EXP2 | 98.56, 97.23, 88.26| 88.35, 98.07, 85.72| 57.52, 94.75, 90.39| 57.15, 89.12, 85.25 | 57.66, 92.77, 86.15| 79.60, 95.75, 82.18| [exp2_mnist_5](https://github.com/krishnakalyan3/Scripts/blob/master/adversarial/log/exp2_mnist_5.txt)



=======
>>>>>>> 59ac7315df6721dad9f3a5a9f24de2484c4cf73d
