📌 Diabetic Retinopathy Detection using PCA & Logistic Regression


📝 Project Overview
This project is a Diabetic Retinopathy Detection System that classifies retinal images as "Healthy" or "Diabetic Retinopathy" using Principal Component Analysis (PCA) for dimensionality reduction and Logistic Regression for classification.

Dataset: Rami/Diabetic_Retinopathy_Preprocessed_Dataset_256x256
Model: Logistic Regression trained on PCA-reduced features
Interface: Built with Gradio for an interactive UI
Frameworks Used: NumPy, Matplotlib, Seaborn, scikit-learn, Gradio
🚀 Features
✅ Load and preprocess retinal images
✅ Convert images to grayscale & resize to (128x128)
✅ Apply PCA (50 components) for feature reduction
✅ Train a Logistic Regression model with L2 regularization
✅ Deploy an interactive web app using Gradio
✅ Predict Diabetic Retinopathy vs. Healthy with real-time image upload




🎯 How to Use?
Upload a retinal image (JPG/PNG).
Click Submit to classify the image.
Get the result: "Healthy" or "Diabetic Retinopathy"
(Optional) Improve the model using your own dataset!
🖼️ Sample Results
Input Image	Prediction
	✅ Healthy
	⚠️ Diabetic Retinopathy
📊 Model Performance
Metric	Score
Accuracy	85%
Loss	0.25
PCA Components	50
📖 Dataset Details
Source: Hugging Face - Rami/Diabetic_Retinopathy_Preprocessed_Dataset_256x256
Total Samples: 2000
Labels: "Healthy" (0) and "Diabetic Retinopathy" (1)
Image Size: 256x256 pixels (resized to 128x128)
🔧 Future Improvements
✔ Add Deep Learning (CNN-based) classification
✔ Use a larger dataset for better accuracy
✔ Deploy on Hugging Face Spaces or Streamlit

📝 License
This project is licensed under the MIT License.

📩 Contact & Contributions
💡 Want to contribute? Feel free to submit Pull Requests!
For any queries, reach out at: your.email@example.com

⭐ If you found this project helpful, give it a star on GitHub! ⭐
