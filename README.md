# Deep Learning-Based Models for Paddy Disease Classification and Segmentation: An Experimental Review



![FIGURE 1. Illustrating (a) the framework for the research process, which encompasses the identification of related works, methodology, results, discussion,
limitations and future work—and their branches, and (b) the process of identifying works related to paddy disease segmentation and classification (literature review,
research gap identification, and analysis of selected classification and segmentation models.)](paper_figures/paper_layout/paper_layout.jpg)

*FIGURE 1. Illustrating (a) the framework for the research process, which encompasses the identification of related works, methodology, results, discussion,
limitations and future work—and their branches, and (b) the process of identifying works related to paddy disease segmentation and classification (literature review,
research gap identification, and analysis of selected classification and segmentation models.)*

## 📌 Segmentation
- **Mask-based paddy disease segmentation dataset (new dataset):** 🆕  
  [segmentation/segmentation_dataset/segmentation_data43_resized_cropped_split](segmentation/segmentation_dataset/segmentation_data43_resized_cropped_split)

- **Image processing-based mask creation codes:**  [segmentation/mask_creation_codes](segmentation/mask_creation_codes)

- **Segmentation code for generation**  
  *(generated masks, confusion matrices, performance metrics — Loss, Accuracy, Precision, Recall, F1-Score, IoU — saved models/weights, pixel distribution plot, augmented image samples, model training history, learning plots)*:  
  [segmentation/segmentation_model_codes/model_generation_confusion_results_code](segmentation/segmentation_model_codes/model_generation_confusion_results_code)

- **Saved segmentation outputs**  
  *(generated masks, confusion matrices, performance metrics — Loss, Accuracy, Precision, Recall, F1-Score, IoU — saved models/weights, pixel distribution plot, augmented image samples, model training history, learning plots)*:  
  [segmentation/segmentation_model_codes/saved_outputs_segmentation](segmentation/segmentation_model_codes/saved_outputs_segmentation)

- **Code for generating 100 bootstrap mean AUC:**  [View here](segmentation/segmentation_model_codes/100_bootstraped_AUC_code)

- **Code for t-test based confidence interval analysis:**  [View here](segmentation/segmentation_model_codes/segmentation_t_tests_from_AUC_code)

- **Mask prediction and heatmaps collage creation code:**  
  [segmentation/segmentation_model_codes/heatmap_predictions_collage_code](segmentation/segmentation_model_codes/heatmap_predictions_collage_code)

- **Mask prediction and heatmaps collage creation results:**  
  [segmentation/segmentation_model_codes/heatmap_predictions_collage_results](segmentation/segmentation_model_codes/heatmap_predictions_collage_results)

- **Code for generating bar plots used in the article:**  [View here](segmentation/segmentation_model_codes/segmentation_results_bar_charts_code)


