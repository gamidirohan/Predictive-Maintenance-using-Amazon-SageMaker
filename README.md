# Predictive Maintenance using Amazon SageMaker

**GitHub Link**: [Predictive-Maintenance-using-Amazon-SageMaker](https://github.com/gamidirohan/Predictive-Maintenance-using-Amazon-SageMaker)

---

## Project Overview
This project focuses on **predictive maintenance** for industrial equipment using **machine learning** and **Amazon SageMaker**. The goal is to predict the **remaining useful life (RUL)** of equipment based on sensor data, enabling proactive maintenance and reducing downtime.

---

## Key Features
1. **Deep Learning Model**: Developed a **deep learning model** using **MXNet** to predict the remaining useful life (RUL) of industrial equipment, achieving **90% accuracy**.
2. **Scalable Deployment**: Deployed the model on **Amazon SageMaker** with **AWS Lambda** for batch inference, ensuring scalability and real-time performance.
3. **Real-World Application**: The project addresses a critical use case in industrial settings, where predictive maintenance can significantly reduce costs and improve operational efficiency.

---

## Technologies Used
- **Machine Learning Frameworks**: MXNet, Scikit-learn  
- **Cloud Platform**: Amazon SageMaker, AWS Lambda  
- **Data Preprocessing**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  

---

## Project Structure
```
Predictive-Maintenance-using-Amazon-SageMaker/
├── data/                   # Dataset used for training and testing
├── notebooks/              # Jupyter notebooks for data exploration and model training
├── scripts/                # Python scripts for data preprocessing and model deployment
├── models/                 # Trained model files
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies
```

---

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/gamidirohan/Predictive-Maintenance-using-Amazon-SageMaker
   cd Predictive-Maintenance-using-Amazon-SageMaker
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebooks**:
   - Open the Jupyter notebooks in the `notebooks/` directory to explore the data, train the model, and evaluate performance.

4. **Deploy the Model**:
   - Follow the instructions in the `scripts/` directory to deploy the model on Amazon SageMaker.

---

## Results
- Achieved **90% accuracy** in predicting the remaining useful life (RUL) of industrial equipment.
- Successfully deployed the model on **Amazon SageMaker**, enabling real-time inference and scalability.

---

## Future Work
- Integrate **anomaly detection** to identify potential equipment failures before they occur.
- Extend the model to support **multimodal data** (e.g., combining sensor data with maintenance logs).

---

## Contributing
Contributions are welcome! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description of your changes.
