# CNN Model Performance Comparison on Flower Dataset

This project aims to compare the performance of a CNN model using different methods and architectural choices on a flower dataset.

## Table of Contents
- [Baseline Model](#baseline-model)
- [L2 Regularization Model](#l2-regularization-model)
- [Batch Normalization Model](#batch-normalization-model)
- [L2 and Batch Normalization Model](#l2-and-batch-normalization-model)
- [L2, Batch Normalization, and Skip Connections Model](#l2-batch-normalization-and-skip-connections-model)
- [ResNet50-like Model](#resnet50-like-model)
- [Transfer Learning Model](#transfer-learning-model)
- [Results](#results)
- [Conclusion](#conclusion)

## Baseline Model
- **Architecture**: VGG16-like
- **Techniques**: No L2 regularization, batch normalization, or skip connections.

## L2 Regularization Model
- **Architecture**: VGG16-like
- **Techniques**: L2 regularization only.

## Batch Normalization Model
- **Architecture**: VGG16-like
- **Techniques**: Batch normalization only.

## L2 and Batch Normalization Model
- **Architecture**: VGG16-like
- **Techniques**: L2 regularization and batch normalization.

## L2, Batch Normalization, and Skip Connections Model
- **Architecture**: VGG16-like
- **Techniques**: L2 regularization, batch normalization, and skip connections.

## ResNet50-like Model
- **Architecture**: ResNet50-like
- **Techniques**: L2 regularization, batch normalization, and skip connections.

## Transfer Learning Model
- **Architecture**: InceptionV3
- **Techniques**: Fine-tuning with flower dataset.

## Results

The transfer learning model using the InceptionV3 architecture achieved the best performance with a training accuracy of 98.9% and a validation accuracy of 96.6%.

## Conclusion

Through extensive experimentation and model comparison, it was found that transfer learning using the InceptionV3 architecture provides superior performance on the flower dataset. While other architectures and techniques brought valuable insights and incremental improvements, leveraging a pre-trained model and fine-tuning it for the specific dataset yielded the most impressive results.
