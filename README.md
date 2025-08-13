# Deep Learning-Based Models for Paddy Disease Classification and Segmentation: An Experimental Review


---

## 📝 Abstract

Early-stage diagnosis of paddy diseases, based on initial visible symptoms, is crucial for minimizing chemical use and preventing the spread of disease. Automated paddy disease diagnosis can facilitate this and contribute to improved crop production. Accurate segmentation of diseased regions is essential for precise severity analysis, and segmentation models can be used to address the challenges related to complex disease patterns. This study analyses the performance and applicability of seven classification models (DenseNet, InceptionV3, Xception, MobileNet, Vision Transformer (ViT), parallel-ViT, and a custom ensemble model of DenseNet121 and Xception) and eight segmentation models (DeepLabv3+, UNet, VGG16 UNet, Inception-ResNetV2 UNet, TransUNet, Attention UNet, MultiResUNet, and Deep Residual UNet) in this domain. A comparative analysis of these models, highlighting their structural differences, advantages, and limitations, is also provided. Given the high computational demands and high data dependency of ViTs, we evaluated whether traditional models, their ensembles, or memory-efficient models could match ViT performance, and found this to be feasible. Additionally, we explored the effect of augmentation intensity on the classification models and identified significant research gaps within this domain. To address the lack of open-access paddy disease segmentation datasets, we created a novel dataset using image-processing techniques. The applicability of the above-mentioned segmentation models was evaluated for paddy diseases using this newly created dataset and we found that the Deep Residual UNet is the most suitable model to be used in resource-constraint applications, considering its quantitative and qualitative performance, model size, and structural advantages and limitations. Furthermore, we investigated the impact of training these segmentation models with a dataset containing more than double the number of augmented images compared to the original dataset. We observed that while the quantitative performance increased with increased data, the qualitative performance degraded in a few cases. Overall, our results can assist researchers in developing effective autonomous systems for paddy disease management.

---

![FIGURE 1. Illustrating (a) the framework for the research process, which encompasses the identification of related works, methodology, results, discussion,
limitations and future work—and their branches, and (b) the process of identifying works related to paddy disease segmentation and classification (literature review,
research gap identification, and analysis of selected classification and segmentation models.)](paper_figures/paper_layout/paper_layout.jpg)

*FIGURE 1. Illustrating (a) the framework for the research process, which encompasses the identification of related works, methodology, results, discussion,
limitations and future work—and their branches, and (b) the process of identifying works related to paddy disease segmentation and classification (literature review,
research gap identification, and analysis of selected classification and segmentation models.)*

---

## Citation Request ✅

If you use our dataset, code, figures, or any other part of this repository in your work, please cite the corresponding published paper(s) appropriately.

**⚠️ Important:** Proper citation acknowledges the effort invested in creating these resources and supports the continued development and sharing of high-quality research tools.

## Please reference the following publications:

1. Mahrin Tasfe, AKM Nivrito, Fadi Al Machot, Mohib Ullah, Faouzi Alaya Cheikh, Habib Ullah,  
*"Deep Learning-Based Models for Paddy Disease Classification and Segmentation: An Experimental Review"*, IEEE Access, 2025.

2. Mahrin Tasfe, AKM Nivrito, Fadi Al Machot, Mohib Ullah, Habib Ullah,  
*"Deep Learning-Based Models for Paddy Disease Identification and Classification: A Systematic Survey"*, IEEE Access, vol. 12, pp. 100862–100891, 2024. doi: [10.1109/ACCESS.2024.3419708](https://doi.org/10.1109/ACCESS.2024.3419708)


---

## 📌 Segmentation
- **Mask-based paddy disease segmentation dataset (new dataset):** 🆕
  [View dataset](segmentation/segmentation_dataset)

- **Image processing-based mask creation codes:**  [View here](segmentation/mask_creation_codes)

- **Segmentation code for generation**  
  *(generated masks, confusion matrices, performance metrics — Loss, Accuracy, Precision, Recall, F1-Score, IoU — saved models/weights, pixel distribution plot, augmented image samples, model training history, learning plots)*:  [View here](segmentation/segmentation_model_codes/model_generation_confusion_results_code)

- **Saved segmentation outputs**  
  *(generated masks, confusion matrices, performance metrics — Loss, Accuracy, Precision, Recall, F1-Score, IoU — saved models/weights, pixel distribution plot, augmented image samples, model training history, learning plots)*:  [View here](segmentation/segmentation_model_codes/saved_outputs_segmentation)

- **Code for generating 100 bootstrap mean AUC:**  [View here](segmentation/segmentation_model_codes/100_bootstraped_AUC_code)

- **Code for t-test based confidence interval analysis:**  [View here](segmentation/segmentation_model_codes/segmentation_t_tests_from_AUC_code)

- **Mask prediction and heatmaps collage creation code:**  [View here](segmentation/segmentation_model_codes/heatmap_predictions_collage_code)

- **Mask prediction and heatmaps collage creation results:**  [View here](segmentation/segmentation_model_codes/heatmap_predictions_collage_results)

- **Code for generating bar plots used in the article:**  [View here](segmentation/segmentation_model_codes/segmentation_results_bar_charts_code)

---

## 📌 Classification

- **Classification model codes and saved results**  
  *(generated masks, confusion matrices, performance metrics — test_loss, test_accuracy, test_f1_score, precision, recall, f1-score — saved models/weights, augmented image samples, model training history, learning plots, training time)*:  
  - **Paddy Doctor dataset:** [View here](classification/classification_data26_code_n_results)  
  - **Rice Leaf Disease dataset:** [View here](classification/classification_data44_code_n_results)

- **Code and results for generating 100 bootstrap mean AUC:**  
  - **Paddy Doctor dataset:** [View here](classification/AUC_result_codes/data26_AUC_codes_n_result)  
  - **Rice Leaf Disease dataset:** [View here](classification/AUC_result_codes/data44_AUC_codes_n_results)

- **Code for t-test based confidence interval analysis:** [View here](classification/t_test_from_AUC_code)

- **Code for generating bar plots used in the article:** [View here](classification/bar_plots_code)

---

## 📈 Figures  
Figures used in this article: [View here](paper_figures)
