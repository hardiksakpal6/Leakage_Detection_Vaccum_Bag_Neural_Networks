# **Vacuum Bagging Leakage Detection with Neural Networks 🤖**

## **Project Overview:**
Welcome to the "Neural Networks for Leakage Detection in Vacuum Bagging" project! In this machine learning endeavor, I aimed to develop a robust model capable of predicting leakage coordinates ("y") within the -1 to 1 range on both the x and y axes. The innovative approach utilized deep neural networks, leveraging the power of artificial intelligence to enhance the accuracy of leakage detection.

## **Input Features:**
The model relies on normalized flow rates ("x") obtained from the four corners of the vacuum bag as input features. This information serves as crucial input for the neural network, enabling it to make predictions about potential leakages.

## **Data Augmentation for Enhanced Performance:**
During the data pre-processing phase, I implemented a powerful technique known as Data Augmentation. By artificially expanding the dataset through rotation and mirroring, I significantly increased the diversity of our training data. The augmented dataset, thus created, outperformed our original dataset, achieving an impressive accuracy of approximately 0.92.

## **Why Data Augmentation?**
Data augmentation is a critical step in the preprocessing pipeline, helping the model generalize better by exposing it to a wider range of scenarios. The rotational and mirrored variations provided the neural network with a richer set of examples, allowing it to learn more robust features and patterns associated with leakage detection.

## **Results and Achievements:**
The deep neural network demonstrated remarkable performance in predicting leakage coordinates, showcasing an accuracy that speaks to the effectiveness of our approach. The model's ability to operate within the -1 to 1 range on both the x and y axes is a testament to its precision and reliability in detecting potential issues during vacuum bagging processes. 

## **Key Features:**
- **Input Features:** Normalized flow rates ("x") from four corners of the vacuum bag.
- **Target Output:** Leakage coordinates ("y") within the -1 to 1 range on both x and y axes.
- **Data Augmentation:** Rotation and mirroring for artificially expanding the dataset.
- **Model Performance:** Achieved accuracy of approximately 0.92.
