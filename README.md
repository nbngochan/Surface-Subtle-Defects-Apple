# Surface Subtle Defects Apple (SSDA) Dataset

This dataset provides images of apple defects for simulating real-world small fruit monitoring. It can be useful for researchers in developing machine learning models for automated defect detection in apples.

## Description

To simulate real-world small fruit monitoring, we collected a dataset of apple defects named Surface Subtle Defects Apple (SSDA). This dataset includes images containing diverse shapes and sizes of distinct defects defined based on their surface presence, such as irregular patterns and morphological or physiological anomalies. The devices and details for data collection are as follows, and the data collection process can be referred to in [Multi-Camera-Based Sorting System for Surface Defects of Apples](https://www.mdpi.com/1424-8220/23/8/3968).

![Original and Annotated images](assets/org_ann.png)

## Data Acquisition Details

* **Apple Type:** Fuji
* **Location:** Jangseong-gun, South Korea
* **Sensor Device:** MX264 CMOS sensing device
* **Camera Device:** acA2240-35uc, Basler AG, Schleswig-Holstein, Germany
* **Image Resolution:** $2448 \times 2048$ pixels
* **Number of Images:** 710 images
* **Variations:** Defect severities captured in the dataset

## Data Access

The SSDA dataset is available for download on this GitHub repository. The dataset is organized into folders as follows:
```
Surface-Subtle-Defects-Apple/
├── images/
│   ├── train/
│   │   - 23945062_20211025_155302_653.jpg  (Training image example)
│   │   - 23945062_20211025_155327_026.jpg  (Training image example)
│   │   - ...
│   └── val/
│       - 23945062_20211025_204433_658.jpg  (Validation image example)
│       - 23945062_20211025_222546_146.jpg  (Validation image example)
│       - ...
└── labels/
    ├── train/
    │   - 23945062_20211025_155302_653.txt  (Training label file)
    │   - 23945062_20211025_155327_026.txt  (Training label file)
    │   - ...
    └── val/
        - 23945062_20211025_204433_658.txt  (Validation label file)
        - 23945062_20211025_222546_146.txt  (Validation label file)
```


**Additional Information:**

*  **Annotation format:** YOLO format (cx, cy, w, h) in text files. You can find more information about the YOLO format [here](https://pjreddie.com/darknet/yolov1/).
*  The dataset contains **568 images** for training and **142 images** for validation (if applicable, replace these numbers with your actual counts).
*  **Downloading the entire repository is recommended** as GitHub does not support downloading individual folders within a repository.


## Contact

For any inquiries about the dataset, please contact [nbngochan99@gmail.com](nbngochan99@gmail.com) or [juhwanlee@jnu.ac.kr](juhwanlee@jnu.ac.kr).


## Potential Applications

* Automated apple defect detection in orchards using machine learning.