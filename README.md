# Skin Cancer Detection using Deep Learning

This project uses Deep Learning and Computer Vision techniques to classify skin cancer images.  
The model is trained using Convolutional Neural Networks (CNNs) to identify different types of skin lesions from image datasets.

---

##  Features

- Skin lesion image classification
- Deep Learning model using TensorFlow/Keras
- Data preprocessing and augmentation
- Visualization of training performance
- Confusion matrix evaluation
- Imbalanced dataset handling using RandomOverSampler

---

##  Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- PIL
- Jupyter Notebook

---

##  Project Structure

Skin-Cancer-Detection/
│
├── Skin_Cancer_Detection.ipynb   # Main notebook
├── requirements.txt             # Dependencies
├── .gitignore                   # Ignored files
└── README.md                    # Project documentation

## Installation
1. Clone the Repository
git clone https://github.com/Coderyash05/Skin-Cancer-Detection.git
cd Skin-Cancer-Detection
2. Create Virtual Environment (Optional)
python -m venv venv

Activate environment:

# Windows
venv\Scripts\activate
# Linux/macOS
source venv/bin/activate
# Install Dependencies
pip install -r requirements.txt

## Run the Project

Launch Jupyter Notebook:

jupyter notebook

Open:

Skin_Cancer_Detection.ipynb
## Model Workflow
Load and preprocess skin lesion images
Handle class imbalance using oversampling
Build CNN model
Train the model
Evaluate performance
Visualize results using confusion matrix and graphs
## Evaluation Metrics
Accuracy
Loss
Confusion Matrix
Classification Performance
## Future Improvements
Deploy model as a web application
Add real-time image prediction
Improve accuracy using transfer learning
Use larger medical datasets
Build mobile-friendly interface
#3 Disclaimer

This project is for educational and research purposes only.
It should not be used as a substitute for professional medical diagnosis.

## Contributing

Contributions are welcome!

Fork the repository
Create a feature branch
Commit changes
Open a pull request
## License

This project is licensed under the MIT License.
