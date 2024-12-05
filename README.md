# Cover Letter Generator

This project is a **Streamlit-based web application** that generates professional, tailored cover letters using **OpenAI's API**. Users can upload their resume in PDF or Word format and input a job description to create a customized cover letter in seconds.

## Features
- **Resume Parsing**: Extracts text from PDF and DOCX files using `PyMuPDF` and `python-docx`.
- **AI-Powered Generation**: Uses the `gpt-3.5-turbo` model from OpenAI to create a personalized cover letter.
- **User-Friendly Interface**: Built with Streamlit for an interactive experience.
- **Download Option**: Save the generated cover letter as a DOCX file.

## Tech Stack
### Backend
- **Python**: Core programming language.
- **OpenAI API**: For AI-powered text generation.
- **PyMuPDF** (`fitz`): For PDF text extraction.
- **python-docx**: For handling Word document text extraction.

### Frontend
- **Streamlit**: Framework for building the web application interface.

### Tools
- **Virtual Environment**: Recommended for dependency isolation.
- **Git**: For version control.
- **VS Code**: Recommended IDE for development (optional).

## Requirements
Install the required dependencies using the `requirements.txt` file:
```bash
pip install -r requirements.txt


## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/MayuriGhongade/Cover_Letter_Generator.git
   cd Cover_Letter_Generator
   ```
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```
4. Enter the job description and upload your resume (PDF or DOCX format).
5. Click **Generate Cover Letter** to create the letter.
6. Click **Download as DOCX** to save the generated cover letter.

## Example
1. Input a job description in the provided text area.
2. Upload your resume in PDF or DOCX format.
3. The app will generate a customized cover letter based on the input.

