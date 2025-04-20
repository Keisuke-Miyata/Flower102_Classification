# 🌸 Flower102 Image Classification (EfficientNetB2 + Hugging Face Deployment)

This project demonstrates how to classify flower images from the [Oxford Flower102 dataset](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html) using a pretrained **EfficientNetB2** model with **PyTorch**, and deploy the trained model to **Hugging Face Spaces**.

The entire workflow—from data processing and model training to evaluation and deployment—is available in two Google Colab notebooks in this repository.

---
## 📂 Files in This Repo

- flower102_classification.ipynb:
    - Experimental notebook to explore the entire pipeline.
    - Works with 3 sample classes for testing.
    - Includes: dataset prep, training, model comparison, predictions, timing, saving, and exporting.
- flower102_classification_full.ipynb:
    - Production-ready version.
    - Modified to classify all 102 flower classes from the dataset.
    - Focused and minimal for deployment.
---
## 🌐 Demo and files on Hugging Face
Try out the live demo here:
- **[3-class Flower Classifier (Experimental)](https://huggingface.co/spaces/Keitarou1003/3flowers_classification)**
    - **[Hugging Face Repository(3-class)](https://huggingface.co/spaces/Keitarou1003/3flowers_classification/tree/main)**
      
- **[102-class Flower Classifier (Full Version)](https://huggingface.co/spaces/Keitarou1003/Flower102_classification)**
    - **[Hugging Face Repository(102-class)](https://huggingface.co/spaces/Keitarou1003/Flower102_classification/tree/main)**

---
## 📁 Project Setup

Since this project is based on **Google Colab**, there is **no fixed folder structure** in the repository. However, running the notebook will dynamically generate the required directories such as:

```
/data/
    /flowers102/
    /3_types_of_flowers_10%/
    /3_types_of_flowers_20%/
    /3_types_of_flowers_100%/

models/
    pretrained_effnetb2_feature_extractor_3_types_of_flowers_100%.pth
```
---
## 🚀 Quick Start
1. Open the Colab notebook from this repo:
2. Run all cells sequentially. The notebook will:
    - Download and prepare the dataset
    - Train the model
    - Save the model
    - Predict on test images
    - Export the model for deployment
3. Deploy to Hugging Face using the exported model and interface code.
---

## 🧪 Model Details

- **Architecture**: EfficientNetB2 (feature extractor)
- **Framework**: PyTorch
- **Classes**:  Either 3(test) or 102 flower types (full dataset)

---

## 📦 Dependencies

All dependencies are handled within the Colab environment. 

---

## 📜 License
This project is licensed under the MIT License.

