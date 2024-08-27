# Summa-Rise: A Text Summarization Tool

## Overview

**Summa-Rise** is a powerful Text Summarization Tool designed to generate concise summaries from lengthy documents using advanced Natural Language Processing (NLP) and Machine Learning (ML) techniques. Built with Python, it leverages the `spaCy` library for text processing and `Tkinter` for an intuitive graphical user interface (GUI), making it accessible and easy to use.

## Features

- **Automated Summarization**: Quickly generate concise summaries from large text inputs.
- **Customizable Output**: Users can specify the desired number of sentences in the summary.
- **NLP-Powered**: Utilizes `spaCy` for deep text analysis, including tokenization, part-of-speech tagging, and dependency parsing.
- **User-Friendly Interface**: A simple and intuitive GUI built with `Tkinter`.
- **Performance Metrics**: Evaluates summary quality using ROUGE scores.

## Installation

### Prerequisites

Ensure you have Python 3.6+ installed. The following Python libraries are required:

- `spaCy`
- `Tkinter` (pre-installed with Python)
- `pandas`
- `heapq`
- `rouge`

### Installation Steps

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/deoRishi/Summa-Rise-A-Text_Summarization-Tool-.git
    cd Summa-Rise-A-Text_Summarization-Tool-
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Download spaCy Model**:
    ```bash
    python -m spacy download en_core_web_sm
    ```

## Usage

1. **Run the Application**:
    ```bash
    python summarization_tool.py
    ```

2. **Input Text**:
    - Paste the text you want to summarize into the text box.
    
3. **Set Summary Length**:
    - Enter the number of sentences you want in the summary.

4. **Generate Summary**:
    - Click the "Summarize" button to generate the summary.

5. **View Results**:
    - The summary will be displayed in the result box.

## Methodology

The tool processes the input text using a series of NLP techniques:
- **Text Preprocessing**: Involves tokenization, stop word removal, lemmatization, and frequency counting.
- **Sentence Ranking**: Sentences are ranked based on normalized word frequencies.
- **Summary Generation**: The top `n` ranked sentences are selected to form the final summary.

## Evaluation

The summaries are evaluated using the ROUGE metric, which measures the overlap of n-grams between the generated summary and reference summaries, ensuring accuracy and contextual relevance.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Thanks to the developers of `spaCy`, `Tkinter`, and other libraries that made this project possible.
- Inspired by numerous research papers on text summarization techniques.

## Contact

For any questions or feedback, please reach out to [deoghariarishikesh2005@gmail.com](mailto:deoghariarishikesh2005@gmail.com).
