# AI Powered Medical Diagnosis System

This project implements an AI-powered medical diagnosis system to help in diagnosing various diseases based on the input symptoms. It uses machine learning models to predict potential diseases based on patient data. This system is designed to assist healthcare professionals by providing quick and accurate disease predictions to support their diagnosis.

## Features

- Disease Prediction: Uses AI models to predict diseases based on symptoms inputted by the user.
- User-Friendly Interface: Simple interface to input symptoms and get predictions.
- Accuracy: The system provides predictions based on the trained data, offering quick diagnostic support.

## Technologies Used

- Python: The core programming language used for building the application.
- Machine Learning Libraries:
  - scikit-learn: For building machine learning models.
  - pandas: For handling and manipulating datasets.
  - numpy: For numerical operations.
  - matplotlib and seaborn: For data visualization.
  
## Installation

### 1. Clone the repository

```bash
git clone https://github.com/divyansh7718/Implementation-of-AI-Powered-Medical-Diagnosis-System.git
cd Implementation-of-AI-Powered-Medical-Diagnosis-System
```

### 2. Install dependencies

It is recommended to use a virtual environment. If you don't have `virtualenv` installed, you can install it with:

```bash
pip install virtualenv
```

Then, create a virtual environment and activate it:

```bash
virtualenv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

### 3. Run the Application

After installing the necessary dependencies, you can run the application.

For a web-based version (if implemented):

```bash
python app.py  
```

### 4. Access the system

Open your browser and go to `http://localhost:5000`.

## Usage

1. Start the application.
2. Input the symptoms you're experiencing.
3. The model will process the input and provide a disease prediction.
4. The predicted disease can be used to guide further diagnostic steps.

## Dataset

If you used any dataset for training the model, be sure to provide details here.

  Dataset Name: diabetes_data, heart_disease_data, hypothyroid, parkinson, surveylung cancer and more.
  


## Future Enhancements

- Integration of a larger dataset for better accuracy.
- Implementation of additional machine learning models for improved predictions.
- Adding support for more diseases and symptoms.
- A mobile application interface for ease of access.
  
## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

Distributed under the MIT License. See `LICENSE` for more information.
