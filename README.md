# Detecting Coronavirus Infections through Chest X-Ray Images
This repository contains code and results for COVID-19 classification assignment by
Deep Learning Spring 2020 course offered at Information Technology University,
Lahore, Pakistan. This assignment is only for learning purposes and is not intended to
be used for clinical purposes.

## Dataset Link
[Click here to to Download the Dataset.](https://drive.google.com/file/d/1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK/view)

### Dataset for Focal Loss
[Click here to to Download the Dataset.](https://drive.google.com/file/d/1eytbwaLQBv12psV8I-aMkIli9N3bf8nO/view)


## Task-1: VGG-16
Using a Learning Rate of 0.001 and Momentum of 0.9, Following were the Results:
- **Training Accuracy**: 95%
- **Validation Accuracy**: 92%
- **Testing Accuracy**: 96%

## Task-1: ResNet-18
Using a Learning Rate of 0.001 and Momentum of 0.9, Following were the Results:
- **Training Accuracy**: 87%
- **Validation Accuracy**: 83%
- **Testing Accuracy**: 91%
- **F1 Score**: 0.9255

**Training Accuracy Curve**
![Training Accuracy Curve](https://github.com/bscs16033/bscs16033_COVID19_DLSpring2020/blob/master/results/task1_resnet18_training_accuracy_curve.png)

**Training Loss Curve**
![Training Loss Curve](https://github.com/bscs16033/bscs16033_COVID19_DLSpring2020/blob/master/results/task1_resnet18_training_loss_curve.png)

**Validation Accuracy Curve**
![Validation Accuracy Curve](https://github.com/bscs16033/bscs16033_COVID19_DLSpring2020/blob/master/results/task1_resnet18_validation_accuracy_curve.png)

**Validation Loss Curve**
![Validation Loss Curve](https://github.com/bscs16033/bscs16033_COVID19_DLSpring2020/blob/master/results/task1_resnet18_validation_loss_curve.png)

**Confusion Matrix on Test Data**
![Confusion Matrix on Test Data](https://github.com/bscs16033/bscs16033_COVID19_DLSpring2020/blob/master/results/task1_resnet18_confusion_matrix.png)


## Task-2: VGG-16
Using a Learning Rate of 0.001 and Momentum of 0.9, Following were the Results:
- **Training Accuracy**: 94%
- **Validation Accuracy**: 92%
- **Testing Accuracy**: 97%
- **F1 Score**: 0.9792

**Training Accuracy Curve**
![Training Accuracy Curve](https://github.com/bscs16033/bscs16033_COVID19_DLSpring2020/blob/master/results/task2_vgg16_training_accuracy_curve.png)

**Training Loss Curve**
![Training Loss Curve](https://github.com/bscs16033/bscs16033_COVID19_DLSpring2020/blob/master/results/task2_vgg16_training_loss_curve.png)

**Validation Accuracy Curve**
![Validation Accuracy Curve](https://github.com/bscs16033/bscs16033_COVID19_DLSpring2020/blob/master/results/task2_vgg16_validation_accuracy_curve.png)

**Validation Loss Curve**
![Validation Loss Curve](https://github.com/bscs16033/bscs16033_COVID19_DLSpring2020/blob/master/results/task2_vgg16_validation_loss_curve.png)

**Confusion Matrix on Test Data**
![Confusion Matrix on Test Data](https://github.com/bscs16033/bscs16033_COVID19_DLSpring2020/blob/master/results/task2_vgg16_confusion_matrix.png)

## Pre-Trained Model Links for Focal Loss
### Focal Loss: VGG16
[Click here to to Download the VGG-16.](https://drive.google.com/open?id=1rEMnI7naUXEgu9JygASOp-tcuSThH-bf)

### Focal Loss: ResNet18
[Click here to to Download the ResNet-18.](https://drive.google.com/open?id=1-1IHWNW2fZAqJZSkV6QdwGjJJ4DQaEZ4)
