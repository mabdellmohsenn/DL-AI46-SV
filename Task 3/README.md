# Intel Image Classification — Deep Learning Comparison

This project compares multiple deep learning approaches for the **Intel Image Classification dataset**.

Dataset Link: [Intel Image Classification Dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)

## Models Evaluated

- Multi-Layer Perceptron (MLP)
- CNN trained from scratch
- Regularized CNN
- Transfer Learning (Pretrained CNN)

Transfer learning experiments include:
- FC Only (classifier training)
- Finetune Last Layers
- Finetune All Layers

## Results

| Model | Test Accuracy |
|------|---------------|
| MLP | 55.10% |
| CNN (from scratch) | 82.23% |
| CNN (Regularized) | 83.27% |
| CNN (Alt. Architecture) | 75.37% |
| Transfer Learning – FC Only | 87.80% |
| **Transfer Learning – Finetune Last Layers** | **91.70%** |
| Transfer Learning – Finetune All | 88.83% |

**Best Model:** Transfer Learning with finetuning of the last layers.

## Tech Stack

##### Check the requirements.txt for exact libraries with their versions.

## Author

Mohamed Abdelmohsen Soliman