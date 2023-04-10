# DETR Fine-tuning for Custom Object Detection
This repository contains a Jupyter Notebook demonstrating the fine-tuning of the DETR (Detection TRansformer) model for custom object detection tasks. DETR is an end-to-end object detection model that utilizes the Transformer architecture, which was originally designed for natural language processing tasks.

# Notebook Overview

The notebook in this repo guides you through the following steps:

- Import necessary libraries: Import all required libraries such as PyTorch, Torchvision, and Hugging Face Transformers.

- Load and preprocess the custom dataset: Load your custom dataset and convert the annotations to the COCO format, which is compatible with DETR.

- Instantiate the DETR model: Instantiate the pre-trained DETR model from the Hugging Face Model Hub, and modify the model's final layer to match the number of classes in your custom dataset.

- Fine-tune the DETR model: Train the DETR model on your custom dataset using PyTorch Lightning. In my case, I am using dataset with images captured by Tesla's on board cameras.

- Evaluate the fine-tuned model: Evaluate the fine-tuned DETR model on a validation set and visualize the results.

## Acknowledgements
This notebook is based on the [Object Detection with DETR](https://colab.research.google.com/github/facebookresearch/detr/blob/colab/notebooks/detr_demo.ipynb#scrollTo=Jf59UNQ37QhJ) notebook provided by the original authors of DETR.


