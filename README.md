🩸 BCCD Blood Cell Detection with YOLOv10
This project fine-tunes YOLOv10 on the BCCD dataset to detect three types of blood cells:

Red Blood Cells (RBCs)
White Blood Cells (WBCs)
Platelets
It also includes a web app built with Gradio for easy interaction.

🚀 Live Demo
Check out the deployed web app on Hugging Face:
[BCCD Blood Cell Detection App](https://huggingface.co/spaces/Diksha333/bccd-blood-cell-detection)

📥 Dataset
Source: BCCD Dataset
Classes: RBC, WBC, Platelet
Images: 364 images for training and testing

📁 Project Structure
BCCD-Blood-Cell-Detection/
├── app.py                # Gradio App for Inference
├── requirements.txt      # Dependencies
├── best.pt               # Fine-tuned YOLOv10 Model (Not Uploaded, Link Below)
└── README.md
Model Weights
The best.pt file is too large to upload to GitHub. Download it from the link below:

[🔗 Download best.pt](https://drive.google.com/drive/folders/1VjgQPBxJVfWxxYO975pTk0PvhHwjskCy?usp=drive_link)

🏗️ Installation and Setup

Clone the Repository:
git clone https://github.com/DikshaKapse/BCCD-Detection.git
cd BCCD-Blood-Cell-Detection
Install Dependencies:

pip install -r requirements.txt
Download Model Weights:

Place the downloaded best.pt file inside the project folder.

Run the App:
python app.py
Access the App:

Open the URL shown in the terminal (usually http://127.0.0.1:7860) in your browser.

Technologies Used
YOLOv10
Python
Ultralytics
Gradio
Google Colab

References
YOLOv10 Documentation
Gradio Documentation
BCCD Dataset
