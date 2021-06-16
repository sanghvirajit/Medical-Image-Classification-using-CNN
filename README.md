# Medical-AI
# Image-Classification-using-CNN

![index](https://user-images.githubusercontent.com/69073063/122219516-cc78ce80-ceaf-11eb-9907-40d813d810c9.png)

Pneumonia detection from X-ray images using Convolution Neural Network

Content

The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

![Screenshot_20210616_141819](https://user-images.githubusercontent.com/69073063/122218143-693a6c80-ceae-11eb-9ba0-b93199aaa355.png)

A Convolution neural network was build using keras and Tensorflow

![Screenshot_20210616_142047](https://user-images.githubusercontent.com/69073063/122218813-190fda00-ceaf-11eb-96b4-ee5b240e54a6.png)

Evaluation metrics:

![Screenshot_20210616_142202](https://user-images.githubusercontent.com/69073063/122218847-23ca6f00-ceaf-11eb-8005-d6797acf426d.png)

visualization of some of the predicted images with percentage %

![Screenshot_20210616_142122](https://user-images.githubusercontent.com/69073063/122218901-2d53d700-ceaf-11eb-9db3-98b7a8e7d2a9.png)

Did able to achieve the training accuracy of **96.68 %** and the testing accuracy of **93.10 %**. That's pretty decent, considering the size of the dataset.
