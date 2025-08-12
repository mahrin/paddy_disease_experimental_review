# Deep Learning-Based Models for Paddy Disease Classification and Segmentation: An Experimental Review



![FIGURE 1. Illustrating (a) the framework for the research process, which encompasses the identification of related works, methodology, results, discussion,
limitations and future work—and their branches, and (b) the process of identifying works related to paddy disease segmentation and classification (literature review,
research gap identification, and analysis of selected classification and segmentation models.)](paper_figures/paper_layout/paper_layout.jpg)

*FIGURE 1. Illustrating (a) the framework for the research process, which encompasses the identification of related works, methodology, results, discussion,
limitations and future work—and their branches, and (b) the process of identifying works related to paddy disease segmentation and classification (literature review,
research gap identification, and analysis of selected classification and segmentation models.)*

## 📌 Segmentation
- **Mask-based paddy disease segmentation dataset (new dataset):** 🆕
  [View dataset](segmentation/segmentation_dataset/segmentation_data43_resized_cropped_split)

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
