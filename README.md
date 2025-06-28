🧬 HematoVision | Blood Cell Classification Using Transfer Learning
HematoVision is an intelligent deep learning web application designed to classify blood cells into four key types: Eosinophils, Lymphocytes, Monocytes, and Neutrophils. Leveraging transfer learning with pre-trained CNN models, it delivers high-accuracy and rapid predictions.

🔍 Project Overview
🎯 Objective: Build a scalable and precise model for automated blood cell classification using Convolutional Neural Networks (CNNs) combined with transfer learning.

🗂 Dataset: Kaggle Blood Cell Dataset

🚀 Method: Transfer learning with fine-tuned CNN architectures like MobileNetV2 and VGG16

🧪 Prediction Flow:
Upload a white blood cell image → Model processes the image → Output: Predicted cell type (e.g., "Neutrophil")

📁 Project Structure
HematoVision/

├── app.py → Flask backend application

├── Blood cell.h5 → Trained Keras model file

├── requirements.txt → List of required Python packages

├── templates/

│ ├── home.html → Image upload page

│ └── result.html → Prediction result display

├── static/ → Temporary storage for uploaded images

└── README.md → Project documentation

💻 Setup Instructions

✅ Option A: Run Locally

Clone this repository from GitHub

Open a terminal and navigate into the project folder

Run: pip install -r requirements.txt

Start the Flask app with: python app.py

Open your browser at: http://localhost:5000

🛠 Option B: Run in Visual Studio Code (VS Code)

Open the HematoVision folder in VS Code

Open the integrated terminal

(Optional) Set up a virtual environment

Run: pip install -r requirements.txt

Launch the app: python app.py

Visit: http://127.0.0.1:5000 in your browser

🌐 Option C: Run on Google Colab

Install necessary libraries in the Colab environment

Upload these files:

Blood cell.h5

home.html

result.html

app.py

Run the app: python app.py

Access it via ngrok public URL

🧠 Use Case Scenarios
HematoVision can be used in multiple real-world scenarios. In diagnostic laboratories, it helps automate the time-consuming task of white blood cell classification, improving accuracy and efficiency. In remote consultation setups, it enables quick and reliable cell-type prediction that supports telemedicine workflows. Additionally, the system is useful in educational environments, assisting students and lab technicians in understanding and verifying cell classifications interactively.

🧰 Tech Stack
The frontend of the application is built using HTML and optionally styled with Bootstrap. The backend is powered by Flask and Flask-ngrok. The deep learning models are developed using TensorFlow and Keras, specifically utilizing MobileNetV2 and VGG16 with transfer learning. For hosting, the application can run seamlessly on Google Colab with ngrok providing internet access to the local server.

📦 Requirements

flask

flask-ngrok

tensorflow

numpy

Pillow

ngrok

Install all dependencies using:

pip install -r requirements.txt

📫 Contact Shaik Rucksar 📧 
 srucksar@gmail.com 
