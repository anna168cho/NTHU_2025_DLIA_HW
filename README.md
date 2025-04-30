# NTHU_2025_DLIA_HW

## **Intro**
This is a repository for NTHU_2025_DLIA, where I'll put my work for this course.

---

## **Table of content**
1. [HW2](#HW2)  
2. [HW3](#HW3)  
3. [HW4](#HW4)   

---

## **HW2**
1. (20 pts) Select 2 hyper-parameters of the artificial neural network used in Lab 2 and set
3 different values for each. Perform experiments to compare the effects of varying these
hyper-parameters on the loss and accuracy metrics across the training, validation, and test
datasets. Present your findings with appropriate tables.
2. (20 pts) Based on your experiments in Question 1, analyze the outcomes. What
differences do you observe with the changes in hyper-parameters? Discuss whether these
adjustments contributed to improvements in model performance, you can use plots to
support your points. (Approximately 100 words.)
3. (20 pts) In Lab 2, you may have noticed a discrepancy in accuracy between the training
and test datasets. What do you think causes this occurrence? Discuss potential reasons for
the gap in accuracy. (Approximately 100 words.)
4. (20 pts) Discuss methodologies for selecting relevant features in a tabular dataset for
machine learning models. Highlight the importance of feature selection and how it can
impact model performance. You are encouraged to consult external resources to support
your arguments. Please cite any sources you refer to. (Approximately 100 words, ,
excluding reference.)
5. (20 pts) While artificial neural networks (ANNs) are versatile, they may not always be
the most efficient choice for handling tabular data. Identify and describe an alternative
deep learning model that is better suited for tabular datasets. Explain the rationale behind
its design specifically for tabular data, including its key features and advantages. Ensure
you to reference any external sources you consult. (Approximately 150 words, excluding
reference.)

---

## **HW3**
1. (10 points) Download the MVTec Anomaly Detection Dataset from Kaggle (here).
Select one type of product from the dataset. Document the following details
about your dataset:
• Number of defect classes.
• Types of defect classes.
• Number of images used in your dataset.
• Distribution of training and test data.
• Image dimensions.
2. (30 points) Implement 4 different attempts to improve the model's performance
trained on the dataset you choose in previous question. Ensure that at least one
approach involves modifying the pre-trained model from TorchVision.
Summarize the outcomes of each attempt, highlighting the best performing
model and the key factors contributing to its success. You may also need to
describe other hyperparameters you use in your experiment, like epochs,
learning rate, and optimizer. (Approximately 150 words.)
3. (20 points) In real-world datasets, we often encounter long-tail distribution (or
data imbalance). In MVTec AD dataset, you may observe that there are more
images categorized under the 'Good' class compared to images for each defect
class. (Approximately 150 words.)
(i) (5 points) Define what is 'long-tail distribution.'
(ii) (15 points) Identify and summarize a paper published after 2020 that
proposes a solution to data imbalance. Explain how their method could be
applied to our case.
4. (20 points) The MVTec AD dataset's training set primarily consists of 'good'
images, lacking examples of defects. Discuss strategies for developing an
anomaly detection model under these conditions. (Approximately 100 words.)
5. For the task of anomaly detection, it may be advantageous to employ more
sophisticated computer vision techniques such as object detection or
segmentation. This approach will aid in identifying defects within the images
more accurately. Furthermore, there are numerous open-source models
designed for general applications that can be utilized for this purpose, including
YOLO-World (website) and SAM (website). (Approximately 150 words.)
(i) (10 points) To leverage these powerful models and fine-tune them using our
dataset, it is necessary to prepare specific types of datasets. What kind of
data should be prepared for object detection and for segmentation.
(ii) (10 points) Why are these models suitable for fine-tuning for our custom
dataset?

---

## **HW4**
1. (15 points) Experiment with different window sizes and steps. Train the model
using 3 different combinations of window size and step. Evaluate the Mean
Squared Error (MSE) for each configuration. Report the MSEs using a table and
analyze the results. (Approximately 100 words.)
2. (Approximately 200 words.)
(i) (15 points) Include 'Volume' as an additional input feature in your model.
Discuss the impact of incorporating 'Volume' on the model's performance.
(ii) (15 points) Explore and report on the best combination of input features that
yields the best MSE. Briefly describe the reasons of your attempts and
analyze the final, optimal input combination.
3. (15 points) Analyze the performance of the model with and without normalized
inputs in Lab 4. You can use experimental results or external references (which
must be cited) to support your conclusions on whether normalization improves
the model's performance. (Approximately 100 words.)
4. (10 points) Why should the window size be less than the step size in Lab 4? Do
you think this is correct? If you use external sources, please include references
to support your response. (Approximately 50 words.)
5. (15 points) Describe one method for data augmentation specifically applicable
to time-series data. Cite references to support your findings. (Approximately 100
words.)
6. Discuss how to handle window size during inference in different model
architectures (approximately 150 words):
(i) (5 points) Convolution-based models
(ii) (5 points) Recurrent-based models
(iii) (5 points) Transformer-based models
---

