# Resume Matching System

This project implements a resume matching system using Natural Language Processing (NLP) and Machine Learning. The system reads resumes and job descriptions, preprocesses the text data, converts it to numerical features using TF-IDF, and trains a logistic regression model to categorize the resumes. Additionally, it calculates the cosine similarity between a job description and a resume to determine how well they match.

## Features

- **Text Preprocessing**: Converts text to lowercase, removes punctuation, stops words, and lemmatizes the words.
- **TF-IDF Vectorization**: Converts the preprocessed text into numerical features.
- **Model Training**: Trains a logistic regression model to categorize resumes.
- **PDF Resume Parsing**: Extracts text from PDF resumes.
- **Cosine Similarity Calculation**: Calculates the similarity between job descriptions and resumes.

## Requirements

- Python 3.x
- Pandas
- Scikit-learn
- NLTK
- PyPDF2
- NumPy

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/resume-matching-system.git
    cd resume-matching-system
    ```

2. Install the required packages:
    ```bash
    pip install pandas scikit-learn nltk PyPDF2 numpy
    ```

3. Download the NLTK data:
    ```python
    import nltk
    nltk.download('stopwords')
    nltk.download('wordnet')
    ```

4. Place your `Resume.csv` file in the project directory. The CSV file should contain the resumes and their corresponding categories.

## Usage

1. Preprocess the text data and train the logistic regression model.
2. Extract text from PDF resumes and preprocess it.
3. Input job descriptions and calculate the cosine similarity between job descriptions and resumes to determine match percentages.

## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
