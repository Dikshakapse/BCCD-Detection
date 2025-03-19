# 🩸 BCCD Blood Cell Detection with YOLOv10

This project fine-tunes YOLOv10 on the BCCD dataset to detect three types of blood cells:

- **Red Blood Cells (RBCs)**  
- **White Blood Cells (WBCs)**  
- **Platelets**  

It also includes a web app built with Gradio for easy interaction.  

## 🚀 Live Demo  
Check out the deployed web app on Hugging Face:  
**[BCCD Blood Cell Detection App](https://huggingface.co/spaces/Diksha333/bccd-blood-cell-detection)**  

---

## 📥 Dataset  
- **Source:** [BCCD Dataset](https://github.com/Shenggan/BCCD_Dataset)  
- **Classes:** RBC, WBC, Platelet  
- **Images:** 364 images for training and testing  

---

## 📁 Project Structure  
BCCD-Blood-Cell-Detection/ ├── app.py # Gradio App for Inference ├── requirements.txt # Dependencies ├── best.pt # Fine-tuned YOLOv10 Model (Not Uploaded, Link Below) └── README.md

---

## 🏋️ Model Weights  
The `best.pt` file is too large to upload to GitHub. Download it from the link below:  

[🔗 **Download best.pt**](https://drive.google.com/drive/folders/1VjgQPBxJVfWxxYO975pTk0PvhHwjskCy?usp=drive_link)  

---

## 🏗️ Installation and Setup  

1. **Clone the Repository:**  
```bash
git clone https://github.com/DikshaKapse/BCCD-Detection.git
cd BCCD-Blood-Cell-Detection
2.Install Dependencies:
pip install -r requirements.txt
3.Download Model Weights:
The best.pt file is too large to upload to GitHub. Download it from the link below:

[🔗 Download best.pt](https://drive.google.com/drive/folders/1VjgQPBxJVfWxxYO975pTk0PvhHwjskCy?usp=drive_link)
4.Run the App:
python app.py

5.Access the App:
Open the URL shown in the terminal in your browser.

Technologies Used
YOLOv10
Python
Ultralytics
Gradio
Google Colab

📚 References  
- [YOLOv10 Documentation](https://docs.ultralytics.com/models/yolov10/)  
- [Gradio Documentation](https://gradio.app)  
- [BCCD Dataset](https://github.com/Shenggan/BCCD_Dataset) 
