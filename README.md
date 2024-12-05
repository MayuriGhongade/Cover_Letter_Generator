# Cover Letter Generator

This project is a **Streamlit-based web application** that generates professional, tailored cover letters using **OpenAI API**. Users can upload their resume in PDF or Word format and input a job description to create a customized cover letter in seconds.

## Features
- **Resume Parsing**: Extracts text from PDF and DOCX files using `PyMuPDF` and `python-docx`.
- **AI-Powered Generation**: Uses the `gpt-3.5-turbo` model from OpenAI to create a personalized cover letter.
- **User-Friendly Interface**: Built with Streamlit for an interactive experience.
- **Download Option**: Save the generated cover letter as a DOCX file.

## Requirements
Install the required dependencies using the `requirements.txt` file:
```bash
pip install -r requirements.txt
