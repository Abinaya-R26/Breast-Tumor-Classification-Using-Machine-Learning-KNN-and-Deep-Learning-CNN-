Abstract:
Breast cancer is one of the most common cancers affecting women worldwide, and early detection is vital for 
improving patient outcomes. Ultrasound imaging is frequently used as a diagnostic tool because it is non-invasive, cost-effective, 
and safer compared to modalities such as mammography, particularly for younger patients with dense breast tissue. However, 
interpretation of ultrasound images relies heavily on radiologist expertise, which can be subjective and time-consuming. 
Artificial intelligence offers promising solutions to address these challenges by providing automated, reliable, and efficient 
tumor classification. This study focuses on the classification of breast tumors in ultrasound images into benign and malignant 
categories using two approaches: K-Nearest Neighbor (KNN) and Convolutional Neural Networks (CNN). KNN, a classical 
machine learning algorithm, is applied on handcrafted texture features extracted from Regions of Interest (ROIs) using the 
Gray-Level Co-occurrence Matrix (GLCM). Features such as contrast, correlation, energy, and homogeneity capture textural 
variations within the tumor region. CNN, on the other hand, is a deep learning model that learns discriminative spatial and 
structural patterns directly from the ultrasound images, reducing the need for manual feature engineering. Both models are 
evaluated on breast ultrasound images with corresponding masks that precisely define the tumor boundaries. Performance is 
assessed using widely accepted metrics such as accuracy, sensitivity, specificity, and F1-score. KNN provides a strong baseline 
with interpretable results, while CNN demonstrates the ability to automatically learn complex features that may be difficult to 
handcraft. The work emphasizes the potential of combining machine learning and deep learning approaches to develop robust 
computer-aided diagnosis systems based on ultrasound imaging. Such systems can assist clinicians in achieving faster, more 
consistent, and more accurate breast cancer diagnosis, ultimately contributing to better patient care
