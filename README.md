# **Sports Personalities Classification using Machine Learning**  

## **Project Overview**  
This project is a **machine learning-based image classification system** that identifies and classifies images of five renowned sports personalities. The model leverages **computer vision techniques** and **deep learning algorithms** to accurately recognize athletes from images.  

### **Classified Athletes**  
- 🎾 **Maria Sharapova**  
- 🎾 **Serena Williams**  
- ⚽ **Lionel Messi**  
- 🏏 **Virat Kohli**  
- 🎾 **Roger Federer**  

## **Folder Structure**  

```
├── UI                                  # Frontend code (HTML/CSS/JavaScript)
├── server                              # Python Flask server for API & model integration
├── model                               # Jupyter Notebook for model building & training
    └── sports_classification.ipynb     # Jupyter Notebook for Classification 
    └── requirements.txt                # Python dependencies
├── images_dataset                      # Dataset of images used for training the model
    └── lionel_messi
    └── maria_sharapova
    └── roger_federer
    └── serena_williams
    └── virat_kohli          
└── README.md                           # Project documentation

```



## **Technologies Used**  
- **Python**  
- **Numpy & OpenCV** → Data cleaning & preprocessing  
- **Matplotlib & Seaborn** → Data visualization  
- **Scikit-Learn** → Model building & evaluation  
- **Jupyter Notebook, VS Code** → IDEs used  
- **Flask** → Backend API for model inference  
- **HTML/CSS/JavaScript** → UI development  

## **Setup Instructions**  
### **1️⃣ Clone the Repository**  
```
git clone https://github.com/mayurisampathgiri/image-classification.git
cd image-classification
```

### **2️⃣ Install dependencies**  
```
pip install -r requirements.txt
```

### **3️⃣ Run the Model**  
Navigate to the `model` folder and open the Jupyter Notebook to run the model:  
```bash
cd model
jupyter notebook
```
### **4️⃣ Run the Flask Server**
Once the model is trained, navigate to the server folder and start the Flask server:

```
cd server
python app.py
```
Your backend API should now be running at http://127.0.0.1:5000/.


### **5️⃣ Start the UI**
Navigate to the UI folder and open index.html in a browser or run a local server:
```
cd UI
python -m http.server 8080
```
Visit http://127.0.0.1:8080/ in your browser to interact with the web interface.

### **6️⃣ Test the Web Application**
After starting the Flask server and UI, you can upload images and test the model's ability to classify them as one of the five sports personalities.



-----------------------------------

🚀 **Inspired by [Codebasics YouTube Playlist](https://www.youtube.com/playlist?list=PLeo1K3hjS3uvaRHZLl-jLovIjBP14QTXc)**  
