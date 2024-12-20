# Diabetic Retinopathy Detection

## Project Overview
Diabetic Retinopathy (DR) is a serious condition caused by prolonged high blood sugar levels, leading to damage in the retina and potential vision loss. This project leverages Deep Learning and Artificial Intelligence (AI) to create a system for early detection of Diabetic Retinopathy through retinal image analysis.

## Motivation
The increasing global prevalence of diabetes necessitates advanced, efficient, and scalable diagnostic tools for early detection of DR. Traditional diagnostic methods are labor-intensive, costly, and require specialized expertise. This project aims to mitigate these challenges by employing cutting-edge AI technologies for a non-invasive, accurate, and cost-effective solution.

## Objectives
- Utilize Convolutional Neural Networks (CNNs) to identify diabetic retinopathy in retinal images.
- Develop a robust and scalable system capable of accurate classification.
- Address dataset imbalance through advanced preprocessing techniques.
- Explore ensemble methods to enhance classification accuracy.

## Features
- **Algorithms Used**: EfficientNetV2 (b0, b1, s variants) with a stacking ensemble approach.
- **Evaluation Metrics**: Precision, Recall, F1 Score, Accuracy.
- **Data Augmentation**: Techniques like random flip, rotation, brightness, contrast, and hue adjustments.
- **Dataset**: EyePacs dataset with five DR severity levels.

## System Architecture
The proposed system employs:
1. **EfficientNetV2 Variants**: Models of different scales to capture a range of features.
2. **Stacking Ensemble**: Combines predictions from individual models to improve overall classification accuracy.
3. **Preprocessing**: Includes balancing classes using random oversampling and undersampling, along with data augmentation.

## Results
- The EfficientNetV2 family models showed varied accuracy levels, with the ensemble model achieving the best classification results.
- The system highlights the need for further improvements in handling imbalanced datasets and enhancing feature representation.

## Challenges and Future Scope
- **Challenges**: Imbalanced dataset and difficulty in learning feature representations for minority classes.
- **Future Work**: Explore advanced pooling strategies, integrate both left and right eye images, and improve dataset handling techniques to minimize overfitting.



## Software and Hardware Requirements
- **Software**: Python 3, TensorFlow, Google Colab (for GPU support).
- **Hardware**: NVIDIA A100 GPU with 40GB memory.

## Authors
- **Sreenivasan R. S** (20BTRCA045)
- **Arvind Rathore V.** (20BTRCA008)
- **Sai Ruthvik M.** (20BTRCA029)

**Guide**: Prof. Narasimhayya B. E

## Acknowledgements
This project was carried out at Jain (Deemed-to-be University) under the guidance of faculty members and with the support of the EyePacs foundation for dataset provision.

## References
1. [EfficientNetV2 Architecture](https://ai.googleblog.com/2021/08/efficientnetv2-smaller-models-and.html)
2. [EyePacs Dataset](https://www.kaggle.com/c/diabetic-retinopathy-detection/data)
3. [TensorFlow Documentation](https://www.tensorflow.org/)

---
For further queries, contact the project authors at their respective email addresses.

