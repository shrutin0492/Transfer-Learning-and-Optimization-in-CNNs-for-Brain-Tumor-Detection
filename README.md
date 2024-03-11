# Transfer Learning and Optimization in CNNs for Brain Tumor Detection
The project aimed to develop a robust brain tumor detection system using Convolutional Neural Networks (CNNs) with transfer learning and optimization techniques. The code implemented several CNN architectures, including ResNet50V2, VGG19, and VGG16, to classify brain MRI images as either tumor or non-tumor.

Initially, the dataset was partitioned into training and testing sets, with approximately 20% of the images allocated for testing. Data preprocessing involved image augmentation and normalization to enhance model generalization and performance. Sample images from the dataset were visualized to provide insights into the data.

The models were trained using both the original dataset and augmented data generated during training. Training progress was monitored using callbacks, including model checkpointing and early stopping to prevent overfitting.

Performance evaluation included metrics such as accuracy, loss, and inference time. Both TensorFlow and ONNX runtimes were utilized to assess the models' efficiency. Additionally, confusion matrices were generated to analyze the models' classification performance in detail.

The ResNet50V2, VGG19, and VGG16 models achieved promising results, with accuracies ranging from 72% to 99% on the test dataset. Furthermore, the models demonstrated efficient inference times, particularly when deployed using the ONNX runtime.
