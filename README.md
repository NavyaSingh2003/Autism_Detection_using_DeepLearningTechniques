# Autism_Detection_using_DeepLearningTechniques

This study, along with its implementation, represents a step towards improvement in the analysis of neuroimaging and high-tech equipment for diagnosis at an early stage of the developmental cycle of patients diagnosed with ASD. It explores the class of applications of deep learning techniques from the Inception model family, including V1, V2, V3, and V4, in the context of classification and modeling of involuntary head motion patterns, which can be useful in distinguishing between people diagnosed with ASD and typically developing (TD) peers. Therefore, this technique leverages hierarchical neuroimaging data representation for the purpose of obtaining accurate classification based on pre-trained VGG19 for feature extraction. Multi-scale feature extraction and fine-tuned architectures were employed to process key features in neuroimaging, which include cortical thickness and functional connectivity. Inception V3 is the best among all the Inception models tested. Its AUC was 0.9897 and the accuracy was 96.04%. Obviously, with regard to both accuracy and computation, the inception model performed better when comparing the architectures.                                          
It provides transfer learning with the aim of addressing high dimensions in data while simultaneously reducing dimensional overlap to lower computationally intensive features.
The addition of regularization methods and cross-validation eliminates overfitting in these models, ensuring that they are applied in the clinical sphere. Other reasons include anonymized data and upholding standards for the medical data collected, thus maximizing the credibility of the system. This study proposes an ASD detector that is scalable, cost-effective, and objective; future work could involve making it an automatic diagnostic support mechanism.

METHODOLOGY

Feature Extraction Using VGG19
a) Used the pre-trained VGG19 model on the ImageNet dataset to extract high-level semantic features.

b) Extracted features from the block5_pool layer, which captures hierarchical image representations.

c) Reshaped the extracted features to the input format required by the Inception models(v1, v2, v3, v4).


DESIGN DIAGRAM
C:\users\lenovo\Pictures\Screenshots\Screenshot 2025-03-29 021105.png

COMPARISON
