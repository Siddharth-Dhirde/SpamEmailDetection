# Email Spam Detection

## Description
This project aims to detect spam messages. It provides a web-based interface where users can input a message, and the system predicts whether it's spam or not using a machine learning model.

## Dataset
The dataset used for training and testing the spam detection model is stored in `spam.csv`. 

## Usage
To use the application:
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the application using `streamlit run app.py`.
4. Enter the message in the provided text area and click on the "Predict" button to get the prediction.

## Code
The main code for the project is provided in `app.py`. It utilizes the `streamlit` library for creating the web interface, and the `pickle`, `nltk`, and `scikit-learn` libraries for model loading, text preprocessing, and prediction.

## Preprocessing
The `transform_text` function in `app.py` is responsible for preprocessing the input text. It converts the text to lowercase, tokenizes it, removes stopwords and punctuation, and performs stemming.

## Model
The machine learning model used for spam detection is loaded from `model.pkl`. It is trained using the TF-IDF vectorization technique.

## Requirements
The required Python libraries are listed in `requirements.txt`, including `nltk`, `streamlit`, `scikit-learn`, and `streamlit_lottie`.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing
Contributions to this project are welcome. Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.