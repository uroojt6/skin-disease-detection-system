
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
- User-Friendly Interface**: Designed for ease of use with intuitive navigation.
- Image Upload**: Users can upload an image of a skin lesion for analysis.
- Accurate Classification**: Provides predictions with confidence scores for the detected condition.
- Mobile-Friendly**: Optimized for use on both web and mobile platforms.
- Data Security**: Ensures privacy and security of user-uploaded images.

## Technology Stack
- Frontend: Flutter (for creating a cross-platform mobile application)
- Backend: Python with Flask/Django (for API development)
- Machine Learning Framework: TensorFlow/Keras (model training and inference)
- Database: Firebase/SQL (for user data and logs)

## How It Works
1. Image Preprocessing: Uploaded images are resized and normalized to prepare them for analysis.
2. Model Prediction: A pre-trained CNN model classifies the image into one of the seven skin disease categories.
3. Results Display: The user receives the predicted disease type along with a confidence score.

## Dataset
The model is trained using the HAM10000 dataset, which contains over 10,000 images of various skin lesions. This diverse dataset ensures high model accuracy and generalization.

## Installation
To run this project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/skin-disease-detection-system.git
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
3. Click on the **Analyze** button.
4. View the prediction results and confidence scores.

## Screenshots
Below are some screenshots showcasing the functionality of the **Skin Disease Detection System**:

1. **ERMO**  
   <img src="https://github.com/uroojt6/skin-disease-detection-system/blob/main/IMG-20241010-WA0054.jpg" alt="ERMO" width="300">

2. **Sign up**  
   <img src="https://github.com/uroojt6/skin-disease-detection-system/blob/main/IMG-20241010-WA0055.jpg" alt="Sign up" width="300">

3. **Sign in**  
   <img src="https://github.com/uroojt6/skin-disease-detection-system/blob/main/IMG-20241010-WA0056.jpg" alt="Sign in" width="300">

4.**Image Upload Screen**  
   <img src="https://github.com/uroojt6/skin-disease-detection-system/blob/main/IMG-20241006-WA0055.jpg" alt="Image Upload Screen" width="500">

   
5. **Result**  
   <img src="https://github.com/uroojt6/skin-disease-detection-system/blob/main/IMG-20241006-WA0055.jpg" alt="Result" width="300">

6. **Navigation Menu**  
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
- Frameworks: TensorFlow, Keras, Flask, Flutter
- Special thanks to all contributors and the open-source community!


