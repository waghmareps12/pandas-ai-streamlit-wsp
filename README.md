# Pandas-AI Streamlit Interface

This project is a Streamlit application that integrates with the PandasAI library to provide an interactive interface for data analysis using OpenAI's language model.

## Features

- Upload CSV files for analysis.
- Ask questions about the data using natural language.
- Visualize results with generated charts.
- Maintain a history of prompts for reference.

## Prerequisites

- Python 3.7 or higher
- An OpenAI API key

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Create a `.env` file in the root directory and add your OpenAI API key:
   ```plaintext
   OPENAI_API_KEY='your_openai_api_key_here'
   ```

## Usage

1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

2. Open your web browser and navigate to `http://localhost:8501`.

3. Upload a CSV file in long format (one data point per row).

4. Ask questions about the data in the provided input field.

5. View the results and any generated charts.

## .gitignore

The project includes a `.gitignore` file to prevent sensitive files (like `.env`) and unnecessary files from being tracked by Git.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments

- [Streamlit](https://streamlit.io/)
- [PandasAI](https://github.com/gventuri/pandas-ai)
- [OpenAI](https://openai.com/)
