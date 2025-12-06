🩺 Diabetic Retinopathy Detection Using ResNet50

Deep Learning | Medical Imaging | TensorFlow | Keras

This project focuses on detecting Diabetic Retinopathy (DR)—a diabetes-induced retinal disease—using deep learning on high-resolution retinal fundus images.
Fine-tuned a ResNet50 CNN model on the APTOS 2019 Blindness Detection Dataset to classify images into five severity levels of DR:
0 - No DR

1 -Mild

2 -Moderate

3 -Severe

4 -Proliferative DR

📂 Dataset

The dataset used is the APTOS 2019 Blindness Detection dataset from Kaggle:
🔗 Download here: https://www.kaggle.com/competitions/aptos2019-blindness-detection/data

🚀 Features

✔️ Multiclass classification (5 DR stages)
✔️ Transfer learning with ResNet50
✔️ Circular cropping + Gaussian enhancement
✔️ Real-time augmentation with ImageDataGenerator
✔️ Stratified train/validation split
✔️ Early stopping & learning rate scheduler
✔️ Achieved ~81.7% test accuracy

🧠 Model Architecture

ResNet50 (pretrained on ImageNet, include_top=False)

Global Average Pooling

Dense(2048) + ReLU

Dropout(0.5)

Dense(5) + Softmax

🛠 Technologies Used

Python

TensorFlow & Keras

NumPy, Pandas

OpenCV

Matplotlib

Scikit-learn

🏁 Conclusion

This project demonstrates how deep learning can support early diagnosis of diabetic retinopathy by analyzing retinal fundus images. With further improvements and clinical validation, the model can be integrated into AI-assisted screening tools.
