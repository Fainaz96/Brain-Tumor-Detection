# Brain-Tumor-Detection
Brain Tumor Detection v1.0 || CNN, VGG-16

1. Project Overview and Objectives¶
The main purpose of this project was to build a CNN model that would classify if subject has a tumor or not base on MRI scan. I used the VGG-16 model architecture and weights to train the model for this binary problem. I used accuracy as a metric to justify the model performance which can be defined as:

Accuracy=Number of correclty predicted imagesTotal number of tested images×100%
Final results look as follows:

Set	Accuracy
Validation Set*	~88%
Test Set*	~80%

* Note: there might be some misunderstanding in terms of set names so I want to describe what do I mean by test and validation set:

validation set - is the set used during the model training to adjust the hyperparameters.
test set - is the small set that I don't touch for the whole training process at all. It's been used for final model performance evaluation.
1.1. Data Set Description
The image data that was used for this problem is Brain MRI Images for Brain Tumor Detection. It conists of MRI scans of two classes:

NO - no tumor, encoded as 0
YES - tumor, encoded as 1
Unfortunately, the data set description doesn't hold any information where this MRI scans come from and so on.

1.2. What is Brain Tumor?
A brain tumor occurs when abnormal cells form within the brain. There are two main types of tumors: cancerous (malignant) tumors and benign tumors. Cancerous tumors can be divided into primary tumors, which start within the brain, and secondary tumors, which have spread from elsewhere, known as brain metastasis tumors. All types of brain tumors may produce symptoms that vary depending on the part of the brain involved. These symptoms may include headaches, seizures, problems with vision, vomiting and mental changes. The headache is classically worse in the morning and goes away with vomiting. Other symptoms may include difficulty walking, speaking or with sensations. As the disease progresses, unconsciousness may occur.



Brain metastasis in the right cerebral hemisphere from lung cancer, shown on magnetic resonance imaging.
![image](https://github.com/Fainaz96/Brain-Tumor-Detection/assets/100863402/75f69559-7f40-4a58-a6c7-fde2be0be383)

Source: Wikipedia
