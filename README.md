
# EFFICIENT LEAF DISEASE CLASSIFICATION AND SEGMENTATION USING MIDPOINT NORMALIZATION TECHNIQUE AND ATTENTION MECHANISM

This repository provides the official implementation of the paper [EFFICIENT LEAF DISEASE CLASSIFICATION AND SEGMENTATION USING MIDPOINT NORMALIZATION TECHNIQUE AND ATTENTION MECHANISM]([https://drive.google.com/file/d/15_jEb3M5U4233wFxr_bBEXXClxXc4M5R/view?usp=sharing](https://drive.google.com/file/d/1blzEka_HFdKkeH6VKx_5vXn-6dA4qbZL/view?usp=sharing)).

## 📝 Abstract
Enhancing diseases detection in plant leaf remains a chal- lenge, particularly with limited data and complex contextual factors. In this work, we present a two-step approach, starting with Mid Point Normalization (MPN) for image preprocess- ing, followed by an attention mechanism to enhance feature recalibration. As a downstream classification task, combining MPN with a Squeeze-and-Excitation (SE) block achieves a high accuracy of 93%, with balanced class-wise performance. Notably, a perfect F1 score for a particular targeted class demonstrates the effectiveness of attention in dynamic feature refinement. For segmentation, integrating the same attention block into the U-Net architecture with MPN-preprocessed images resulted in substantial improvements, yielding a Dice score of 72.44% and an Intersection-over-Union (IoU) of 58.54%, surpassing the baseline U-Net. Our experiments not only delivered higher accuracies but also produced effi- cient, lightweight, and robust models suitable for real-world computer vision applications.

---

## 📂 Dataset
The dataset used in this research can be downloaded from the following link:  
🔗 [Download Dataset](https://data.mendeley.com/datasets/g7fpgj57wc/2)

---

## 🚀 Training
The training process was conducted in **Google Colab**.  
To replicate the training, place the dataset in the appropriate folders and execute the training notebook.

---

## 📊 Evaluation
To evaluate the trained model, follow the same folder structure used in the Colab training file and run the evaluation script.

---

## 🔥 Results
Our model achieved the following performance:

| Model Name                | Macro F1 Score |
|---------------------------|---------------|
| MPN with a Squeeze-and-Excitation (SE) | **0.93** |

---

## 📜 Citation
If you use this work in your research, please cite it as:

```bibtex
@misc{enam2024,
    title={EFFICIENT LEAF DISEASE CLASSIFICATION AND SEGMENTATION USING MIDPOINT NORMALIZATION TECHNIQUE AND ATTENTION MECHANISM},
    author={Enam Ahmed Taufik, Antara Firoz Parsa, Seraj Al Mahmud Mostafa},
    year={2024}
}
