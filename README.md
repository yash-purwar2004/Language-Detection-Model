# Language Detection Model

This project is a Natural Language Processing (NLP) model designed to detect the language of a given text. The model utilizes popular Python libraries such as NumPy, Pandas, and Scikit-learn to preprocess the data, train a classifier, and evaluate its performance.

---

## Features
- Detects the language of input text.
- Preprocesses text data, including cleaning and tokenization.
- Implements a machine learning model for classification.
- Supports evaluation metrics like accuracy, precision, and recall.

---

## Technologies Used
- **Python**: Programming language for the project.
- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and preprocessing.
- **Scikit-learn**: For building and evaluating the machine learning model.

---

## Installation

### Prerequisites
Ensure you have Python 3.7 or higher installed on your system.

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/language-detection.git
   cd language-detection
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Dataset
- **Source**: The dataset used for training and testing contains text samples labeled with their corresponding languages.
- **Format**: CSV file with two columns:
  - `text`: The text sample.
  - `language`: The language label.

---


## Usage
Provide a text input to the application, and the model will predict the language of the text.

Example:
```bash
Input: "Bonjour tout le monde"
Output: "French"
```

---

## Model Training
1. **Data Preprocessing**:
   - Text cleaning: Removing punctuation, numbers, and special characters.
   - Tokenization: Splitting text into words.
   - Vectorization: Converting text into numerical features using techniques like TF-IDF.

2. **Model**:
   - Classifier: Multinomial Naive Bayes (or any suitable classifier).
   - Framework: Scikit-learn.

3. **Evaluation**:
   - Metrics: Accuracy, precision, recall, and F1-score.

---


## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push the branch and create a pull request.

---


Thank you for checking out this project! Happy coding! :tada:

