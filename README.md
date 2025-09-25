# Multi-HAR

A parallel feature fusion-based HAR framework is proposed for classification of single and multi-person activities in the image frames. The proposed framework comprises four steps: pre-processing, feature extraction, fusion and classification, and post-processing. The preprocessing step includes the generation of bounding boxes. The feature extraction step is further divided into two modules: spatial feature extraction module and temporal feature extraction module, which extract spatial and temporal features from input images simultaneously and independently using attention modules and DL algorithms. The third step includes feature fusion of extracted features followed by fully connected layers for classification. The post-processing gives the resultant frames with bounding boxes and generated labels. For the validation of the proposed method, four publicly available datasets, namely, KTH, Weizmann, UCF ARG, and MHAD have been exploited with attained accuracy of 96.25%, 95.88%, 100%, and 92.08%, respectively. 

**Dataset Links**

**KTH Dataset **
Downloaded from: https://www.csc.kth.se/cvap/actions/

**Weizmann Dataset**
Downloaded from: http://www.wisdom.weizmann.ac.il/~vision/SpaceTimeActions.html

**UCF ARG Dataset**
Downloaded from: https://www.crcv.ucf.edu/data/UCF-ARG.php

**MHAD Dataset**
Downloaded from: https://drive.google.com/file/d/1pfnnansy4VAejLRKNhCA8fn9IABarwwz/view
                 Reference Paper: Elharrouss O, Almaadeed N, Al-Maadeed S (2019) Mhad: multi-human action dataset. In Fourth International Congress on Information and Communication Technology: ICICT 2019 1: 333-341
