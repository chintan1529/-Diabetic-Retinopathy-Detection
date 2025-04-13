Diabetic Retinopathy Detection using PCA & Logistic Regression

📝 Project Overview

This project presents an AI-based system to classify retinal fundus images as either Healthy or Diabetic Retinopathy. It uses Principal Component Analysis (PCA) for dimensionality reduction and a custom Logistic Regression model for classification.

Dataset: Rami/Diabetic_Retinopathy_Preprocessed_Dataset_256x256

Model: Logistic Regression trained on PCA-reduced image features

Interface: Built with Gradio for an interactive web UI

Libraries: NumPy, Matplotlib, Seaborn, Scikit-learn, Gradio

🚀 Key Features

📁 Load and preprocess retinal fundus images

🧠 Convert images to grayscale and resize to 128x128

📉 Apply PCA (50 components) for feature extraction and dimensionality reduction

🔢 Train a Logistic Regression model with L2 regularization

🌐 Launch an interactive web app using Gradio

⚡ Real-time prediction: Upload → Classify → Get result

✅ Labels: "Healthy" or "Diabetic Retinopathy"

🎯 How to Use
Clone the repo and install dependencies:

pip install -r requirements.txt
Run the app:

python app.py
Upload a retinal image (JPG/PNG)

Click Submit to classify

View your result: ✅ Healthy or ⚠️ Diabetic Retinopathy

🖼️ Sample Predictions


Input Image	Prediction
Retina_001.jpg	✅ Healthy
Retina_045.jpg	⚠️ Diabetic Retinopathy
📊 Model Performance


Metric	Score
Accuracy	85%
Loss	0.25
PCA Components	50
📖 Dataset Details
Source: Hugging Face

Total Samples: 2,000 images

Labels:

0: Healthy

1: Diabetic Retinopathy

Original Image Size: 256x256

Resized To: 128x128 (for PCA)

🔧 Future Improvements


🤖 Add Deep Learning models (e.g., CNN-based classifiers)

📈 Train on larger and more diverse datasets

☁️ Deploy to Hugging Face Spaces or Streamlit Cloud

🔍 Add Grad-CAM or other visual explainability tools

📜 License


Licensed under the MIT License.

📩 Contact & Contributions


💡 Contributions are welcome! Feel free to open an issue or submit a pull request.
📬 For any queries or collaboration, reach out at: chintanchhajed@gmail.com

⭐ If you found this project helpful, give it a star on GitHub!
