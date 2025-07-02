


---

```markdown
# MemoryMesh - Résumé & Quiz Generator

## Project Overview
MemoryMesh is a Python application that performs intelligent text extraction from various file formats (PDF, PPTX, TXT), summarizes the content, and generates interactive quizzes from the extracted information. It employs an API to assist in generating summaries and quizzes, providing a comprehensive tool for enhancing learning and retention through spaced repetition.

## Installation
To run the MemoryMesh project, ensure you have Python installed on your system (preferably Python 3.7 or higher). Use the following commands to install the required dependencies:

```bash
pip install requests PyPDF2 python-pptx fpdf
```

You can also clone this repository and install the dependencies as follows:

```bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
```

## Usage
To utilize MemoryMesh, follow these steps:

1. **Run the script**:
   ```bash
   python testV2.py
   ```
2. **Choose an action** when prompted:
   - Input `1` for summarizing the document.
   - Input `2` for generating a quiz.
   - Input `3` for both resumo and quiz.

3. **Provide the file path** for a PDF, PPTX, or TXT file when prompted.

4. **Follow on-screen instructions** to interact with the generated quiz.

## Features
- **Multi-format text extraction**: Supports PDF, PPTX, and TXT file formats.
- **Content summarization**: Generates concise summaries of the content in French.
- **Interactive quizzes**: Creates quizzes with multiple-choice questions, true/false questions, and open-ended questions based on the extracted content.
- **Scoring & retention metrics**: Evaluates quiz results and provides insights on memory retention using Ebbinghaus metrics.
- **Export results**: Saves summaries and quiz results as TXT or PDF files.

## Dependencies
The following Python packages are required to run the MemoryMesh application:

- `requests`
- `PyPDF2`
- `python-pptx`
- `fpdf`

These can be automatically installed using the commands in the Installation section.

## Project Structure
Here’s a brief overview of the main components of the project:

- `testV2.py`: The main application script containing all functionalities.
    - **Functions**:
        - `extract_text()`: Extracts text from various document types.
        - `analyze_content()`: Analyzes content for summarization and quiz generation.
        - `present_quiz()`: Facilitates the interactive quiz session.
        - `calculate_retention_metrics()`: Computes memory retention metrics based on quiz results.
        - `save_results()`: Saves the quiz and summary results to the specified formats.

## API Usage
This application interacts with the OpenRouter API for generating content summaries and quizzes. Make sure to set your API_KEY by modifying the `API_KEY` variable. It's recommended to handle sensitive data using environment variables or secure configuration methods.

## Contributing
Contributions to MemoryMesh are welcome! Please fork the repository and make a pull request for improvements or bug fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
For any questions or feedback, feel free to open an issue in this repository. Happy learning!
```
