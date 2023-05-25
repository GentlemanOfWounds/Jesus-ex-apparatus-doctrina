# Jesus-ex-apparatus-doctrina
**Image Caption Generator Using Transfer / Inference Learning, Region-based Convolutional Neural Network Algo’s, and Bidirectional Long- / Short-Term Memory – Recurrent Neural Network Algo's, Open CV’s cv2, & YOLO’s YOLOv3 & YOLOv8 for Augmented Molecular Education**



**Deep Learning for Computer Vision Frameworks Project                                                                                       (JAN2023 – PRESENT)**

**Title:** Image Caption Generator Using Transfer / Inference Learning, Region-based Convolutional Neural Network Algo’s, and Bidirectional Long- / Short-Term Memory – Recurrent Neural Network Algo's, Open CV’s cv2, & YOLO’s YOLOv3 & YOLOv8 for Augmented Molecular Education

**Potential Clients:** 0. Governmental agencies / corporations providing services for the spectrum of visual impairments, 1. News / entertainment media companies, 2. Educational companies / organizations

**Data Source, Format, & Size:** For R-CNN Model Training: publicly available ***Flicker_8k Image Dataset*** of 8_092 images (total size of images = 1.2 GB), each w/ five human-generated captions (total size of captions = 3.32 MB); For YOLO / OpenCV Model Training: 0. publicly available ***Microsoft COCO: Common Objects in Context (COCO) Dataset*** of 328_000 images comprising 2_500_000 labeled instances of 91 object-types that would be easily recognizable by a four-year-old AND 1. publicly available ***dataset of 21_169 scanning electron microscopy (S.E.M.) images (classified into 10 categories)*** produced at *Istituto Officina dei Materiali (IOM) of the Italian National Research Council (CNR) (CNR-IOM)* (Trieste, Italy)

**CRISP-DM Project Description (inc. Business Understanding):** ***Problem:*** According to the World Health Organization, approximately 1.3 billion people globally live with some form of vision impairment. Yet, even people living with blindness and severe vision impairment that cannot be treated are still able to lead independent lives if they access rehabilitation services such as optical magnifiers, Braille text, smartphone wayfinders, and orientation & mobility training with canes. For those individuals using computing services, the ability to discern the content of images encountered on a screen or in real life would be a boon for quality of life. This is particularly true for visually impaired students / scholars of chemical, molecular biological, & macromolecular topics, wherein the visualization of subatomic, atomic, & molecular structures is crucial to optimizing learning the broader material.

   ***Proposed Solution:*** Herein, we utilized transfer / inference learning, region-based convolutional neural network (***R-C.N.N.***) modeling, bidirectional long- / short-term memory (***B-LSTM***) recurrent neural network (***R.N.N.***) modeling, and vanguard computer vision frameworks to produce an API that can caption (detailing the content within the images) submitted images with high accuracy and robustness. Regarding this issue of ameliorating visual impairment, my particular passion is enhancing the educational attainment of visually limited students.

**CRISP-DM Business Objectives:** 0. maximize quality (i.e.: accuracy, sensitivity / recall, specificity, F1 score, & ROC Curve A.U.C.) & robustness of object detection via Region-based C.N.N. model, 1. maximize accuracy & detail of verbal description of detected objects via Bidirectional LSTM-R.N.N., 2. master vanguard framework for natural language processing [Bidirectional Encoder Representations from Transformers (***B.E.R.T.***)] and computer vision (***OpenCV’s cv2 & YOLO's YOLOv8***), 3. minimize project expenses, 4. minimize project duration

**CRISP-DM Business Constraints:** maximize quality & robustness of captioning of varied images (particularly chemical, molecular biological, & macromolecular images)

**Data Science Tools Used:** Python

**Frameworks / Libraries / Packages & Modules Used:** os (for interacting w/ operating system), pickle, json, numpy, pandas, re, tqdm (for progress bars), OpenCV’s cv2 (for image preprocessing), sklearn.model_selection’s train_test_split, various packages & modules from tensorflow’s keras (e.g.: applications, preprocessing, utils, layers, models, optimizers, regularizers), nltk.translate.bleu_score’s corpus_bleu. PIL’s Image, matplotlib's pyplot, YOLO’s YOLOv3, YOLO’s YOLOv8

**Steps Taken:** Transfer-Load ***VGG-16 CNN Model***, Extract Features from Flicker8k Dataset Images, Store Feature in Pickle File, Preprocess Captions, Tokenize Captions, Map Images to Captions, Batch Process Training Images in ***C.N.N.-cum-LSTM Model***, Train Combined Model, Generate Test Caption for Test Images, Process Novel Images in ***C.N.N.-cum-LSTM Model***, Master ***OpenCV’s cv2*** & ***YOLOv8*** and ***B.E.R.T.***

**Roles and Responsibilities:** Responsible for end-to-end conceptualization & implementation: 0. data acquisition & comprehension, 1. model building, augmentation, and evaluation, 2. local deployment, 3. self-guided education

**CRISP-DM Business Benefits:**
0. ***Increased revenue*** via augmented user experience of website / app for a wider range of potential patrons
1. ***Increased revenue*** via enhanced Quality-of-Life of visually impaired users of website / app by augmenting scene comprehension
2. ***Increased electability of political candidate*** client by increasing civic engagement w/ their website / app
3. ***Increased revenue*** via improved company’s / entity's reputation for being broadly inclusive
4. ***Increased revenue*** via heightened concentration & engagement of learners w/ disabilities (e.g.: blindness, legal blindness, color-blindness, A.D.D. / A.D.H.D., Autism Spectrum Disorder)
5. ***Increased revenue*** via optimized comprehension & mastery of chemical, molecular biological, & macromolecular subject matters
