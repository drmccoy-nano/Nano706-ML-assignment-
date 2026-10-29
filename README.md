# Assignment Report: NANO 706 - Systems and Computational Biology

**Topic:** Image Classification and Object Detection using Machine Learning

---

## Part 1: MNIST Handwritten-Digit Classification Results

In this section, three machine learning models were evaluated on the MNIST handwritten digit dataset. The quantitative test accuracies for each model are as follows:

*   **Logistic Regression Accuracy:** **`91.54%`**
*   **Random Forest Accuracy:** **`96.75%`**
*   **Multi-Layer Perceptron (MLP) Accuracy:** **`97.12%`**

### Key Findings:
*   The **Multi-Layer Perceptron (MLP)** model outperformed the others, achieving the highest classification accuracy (**`97.12%`**), proving its excellence in capturing non-linear configurations of handwritten digit data.
*   The **Random Forest** model also performed very strongly, reaching **`96.75%`** accuracy, proving to be a highly competitive and robust non-linear ensemble method.
*   The **Logistic Regression** model had the lowest accuracy (**`91.54%`**), illustrating that linear boundaries are less effective at resolving complex digit patterns compared to tree ensembles and neural networks.

---

## Part 2: YOLOv5 Object Detection Results

For the object detection task, the pre-trained **YOLOv5** model was run on your personal photograph (`IMG_5703.jpg`) containing an office workspace setting. The model successfully detected and localized multiple objects with the following confidence levels:

*   **`tv` (monitor)**: Detected with a confidence score of **`0.82`**
*   **`laptop`**: Detected with a confidence score of **`0.79`**
*   **`keyboard`**: Two separate keyboards detected with confidence scores of **`0.90`** and **`0.29`**
*   **`mouse`**: Two separate mice detected with confidence scores of **`0.77`** and **`0.63`**
*   **`person`**: Your face and upper body were successfully detected with a confidence score of **`0.69`**
*   **`cup`**: Detected with a confidence score of **`0.44`**

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/c82bd086-c369-4a87-ad3e-23fc46a1b5bf" />


### Key Findings:
The pre-trained YOLOv5 model performed excellently on a real-world, personalized image, showing strong generalizability. It accurately separated human features from complex workspace elements (such as screens, dual mice, and customized keyboards) despite varying angles and lighting conditions.
