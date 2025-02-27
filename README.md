# AI_project
#Dataset descripton

This dataset is designed to aid in the diagnosis of **breast cancer**, one of the most prevalent cancers in the world. It includes detailed measurements of cell nuclei extracted from breast mass biopsies. The dataset is widely used in medical research and machine learning to develop diagnostic tools that assist in early and accurate detection of breast cancer.

Each row in the dataset represents a patient’s tumor characteristics, and the columns represent various features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. These features can be grouped into three categories:

1. **Geometric Features:**

- **Radius Mean:** Average radius of the tumor (measured from center to edge).
- **Perimeter Mean:** Length around the tumor boundary.
- **Area Mean:** Total area enclosed within the tumor.


2. **Texture Features:**

- **Texture Mean:** Variation in gray-scale intensity across the tumor’s surface.


3. **Shape and Structure Features:**

- **Smoothness Mean:** Measures how smooth the tumor’s surface is.
- **Compactness Mean:** Describes how tightly packed the tumor cells are.
- **Concavity Mean:** Extent to which the tumor's surface curves inward.
- **Concave Points Mean:** Number of concave points on the tumor's perimeter.
- **Symmetry:** Symmetry between the tumor’s left and right sides.
- **Fractal Dimension:** Measures the tumor boundary’s complexity.

Each feature is provided as a mean, standard error, and worst value (i.e., largest instance of the feature for a particular tumor).

The target variable, **Diagnosis**, indicates the type of tumor:

- **M (Malignant):** Cancerous tumor.
- **B (Benign):** Non-cancerous tumor.


#Acknowledgment

We extend our gratitude to the **University of Wisconsin-Madison** and its researchers for collecting and sharing this dataset, which was originally published by **Dr. William H. Wolberg**. Their work has enabled countless advancements in the early detection of breast cancer, aiding researchers and clinicians in developing better diagnostic tools.

Additionally, we acknowledge the efforts of data scientists and machine learning practitioners who continue to use this data to create predictive models that help identify cancerous tumors at earlier stages, potentially saving lives through timely medical interventions.


#Disease type

Breast cancer is a disease where cells in the breast grow uncontrollably. It is classified into two major types based on its potential to spread:

1. **Malignant Tumors (Cancerous)**
These tumors are:

- **Aggressive**: They grow rapidly and can invade surrounding tissues.
- **Metastatic**: They can spread to other parts of the body, such as lymph nodes, bones, lungs, and liver.
- **Life-threatening**: Require immediate medical intervention, including surgery, chemotherapy, radiation, or targeted therapy.

2. **Benign Tumors (Non-Cancerous)**
These tumors:

- **Do not spread**: They remain localized to the breast.
- **Grow slowly**: Often don’t pose a significant health risk.
- **May require monitoring**: In some cases, surgical removal is needed to prevent discomfort or further growth.

#Common symptoms of Breast Cancer

- Lump in the breast or underarm.
- Change in the size, shape, or appearance of the breast.
- Dimpling of the skin or nipple discharge.
- Persistent breast pain or redness.


#Importance of Early diagnosis

Early detection of breast cancer significantly improves the chances of successful treatment and survival. Diagnostic techniques like mammography, ultrasound, and biopsies, combined with machine learning models developed from datasets like this, play a vital role in identifying cancer at its earliest stages.

# Problem Definition

`Doctors' accuracy in predicting breast cancer from mammograms varies:`



`. Sensitivity (correctly identifying cancer): 75-85%`



`. Specificity (correctly identifying non-cancer): 90-95%`



`Accuracy improves with experience, and AI tools are enhancing diagnostic precision.`



`Task is to Classify breast cancer tumors as malignant or benign using features

extracted from mammograms.`
