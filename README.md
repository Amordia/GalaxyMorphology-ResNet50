# Galaxy Morphology Classification using ResNet50

This repository contains the supervised implementation of galaxy morphology classification using the ResNet50 architecture. It is part of a broader project exploring different methodologies for galaxy morphology classification, including semi-supervised approaches using Convolutional AutoEncoders (CAE) and MoCo.

## Background and Significance

Galaxy morphology studies are a crucial part of astronomical research, aiding our understanding of the universe's history and evolution. However, classifying galaxy morphologies is often intricate and time-consuming, requiring extensive manual effort and expertise. Thus, an effective automated approach for large-scale galaxy morphology data has become an important astronomical research topic.

Recent successes of deep learning and machine learning in image classification and recognition pave the way for automating galaxy morphology classification. Traditional supervised learning methods often require ample labeled data, which can be a luxury in many real-world applications. Also, the unique characteristics of astronomical data, such as high noise levels and imbalances, mean that directly applying existing deep learning models might not yield optimal results.

In the broader context of this research, various methodologies, including the MoCo-based semi-supervised learning algorithm, were explored. This specific repository focuses on the supervised ResNet50 model for galaxy morphology classification, serving as a baseline for comparing other methods.

## Repository Structure

- `src/`: Contains the main source code in Jupyter notebook format.
- `datasets/`: Datasets used for training and validation.
- `results/`: Contains various plots showcasing the model's performance.
- `models/`: Contains the saved weights of trained models.

## Getting Started

1. Clone this repository.
2. Navigate to the project directory.
3. Install the required dependencies.
4. Run the `resnet.ipynb` notebook to train and evaluate the model.

## Results

Refer to the `results/` directory for visualizations such as accuracy, loss, ROC curve, and confusion matrices.

## Related Repositories

- [Convolutional AutoEncoders (CAE) for Galaxy Morphology Classification](https://github.com/Amordia/GalaxyMorphology-CAE.git)
- [MoCo-based Semi-Supervised Learning for Galaxy Morphology Classification](https://github.com/Amordia/GalaxyMorphology-MoCo.git)

## License

This project is licensed under the MIT License.
