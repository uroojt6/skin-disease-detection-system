Below is an updated version of your markdown that highlights your use of a CNN model in greater detail:

```markdown
# Skin Disease Detection System

## Overview
The Skin Disease Detection System is a machine learning-powered application designed to detect and classify various skin diseases based on image data. This project leverages advanced convolutional neural networks (CNNs) to provide accurate and efficient classification for early diagnosis and treatment recommendations.

## Diseases Covered
This application is trained to detect and classify the following skin conditions:
1. Melanocytic Nevi
2. Melanoma
3. Benign Keratosis-like Lesions
4. Basal Cell Carcinoma
5. Actinic Keratoses
6. Vascular Lesions
7. Dermatofibroma

## Features
- **User-Friendly Interface**: Designed for ease of use with intuitive navigation.
- **Image Upload**: Users can upload an image of a skin lesion for analysis.
- **Accurate Classification**: Provides predictions with confidence scores for the detected condition.
- **Mobile-Friendly**: Optimized for use on both web and mobile platforms.
- **Data Security**: Ensures privacy and security of user-uploaded images.

## Technology Stack
- **Frontend:** Flutter (for creating a cross-platform mobile application)
- **Backend:** Python with Flask/Django (for API development)
- **Machine Learning Framework:** TensorFlow/Keras (model training and inference)
- **Database:** Firebase/SQL (for user data and logs)

## CNN Model Architecture
The core of the detection system is built around a convolutional neural network (CNN), which is highly effective for image classification tasks. Key components include:
- Convolutional Layers: Extract complex features from input images using multiple filters.
- Pooling Layers: Reduce the spatial dimensions while preserving the essential features, aiding in computational efficiency.
- Dropout Layers: Prevent overfitting by randomly deactivating neurons during training.
- Fully Connected Layers: Combine extracted features to classify images into one of the seven skin disease categories.

This CNN is trained on the HAM10000 dataset, ensuring robust feature extraction and high classification accuracy.

 How It Works
1. Image Preprocessing:
   Uploaded images are resized and normalized to prepare them for analysis.
2. Model Prediction: 
   A pre-trained CNN model processes the image and classifies it into one of the seven skin disease categories, outputting both the predicted label and a confidence score.
3. Results Display: 
   The user receives the prediction results, complete with confidence scores for informed decision-making.

## Dataset
The model is trained using the HAM10000 dataset, which contains over 10,000 images of various skin lesions. This diverse dataset ensures high model accuracy and generalization.

## Installation
To run this project locally:
1. Clone the repository:
   ```bash
   git clone https://uroojt6/skin-disease-detection-system.git
   cd skin-disease-detection-system
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```

## Usage
1. Launch the application and log in or sign up.
2. Upload an image of the skin lesion.
3. Click on the Analyze** button.
4. View the prediction results and confidence scores.

## Screenshots
Below are some screenshots showcasing the functionality of the Skin Disease Detection System:

1. **ERMO**  
   <img src="https://github.com/uroojt6/skin-disease-detection-system/blob/main/IMG-20241010-WA0054.jpg" alt="ERMO" width="300">

2. **Sign up**  
   <img src="https://github.com/uroojt6/skin-disease-detection-system/blob/main/IMG-20241010-WA0055.jpg" alt="Sign up" width="300">

3. **Sign in**  
   <img src="https://github.com/uroojt6/skin-disease-detection-system/blob/main/IMG-20241010-WA0056.jpg" alt="Sign in" width="300">

4. **Image Upload Screen**  
   <img src="https://github.com/uroojt6/skin-disease-detection-system/blob/main/IMG-20241006-WA0055.jpg" alt="Image Upload Screen" width="300">

5. **Result**  
   <img src="https://github.com/uroojt6/skin-disease-detection-system/blob/main/IMG-20241005-WA0023.jpg" alt="Result" width="300">

6. **Set Reminder**  
   <img src="https://github.com/uroojt6/skin-disease-detection-system/blob/main/IMG-20241005-WA0024.jpg" alt="Set Reminder" width="300">

7. **Navigation Menu**  
   <img src="https://github.com/uroojt6/skin-disease-detection-system/blob/main/IMG-20241010-WA0058.jpg" alt="Navigation Menu" width="300">

## Future Enhancements
- Integration of additional skin conditions.
- Real-time image analysis using smartphone cameras.
- Multilingual support to cater to a global audience.
- Integration with healthcare systems for seamless reporting.

## Contributing
Contributions are welcome! If you have ideas or improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Dataset: [HAM10000](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000)
- Frameworks:TensorFlow, Keras, Flask, Flutter
- Special thanks to all contributors and the open-source community!
