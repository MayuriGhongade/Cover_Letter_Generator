# Cover Letter Generator

This project is a **Streamlit-based web application** that generates professional, tailored cover letters using **OpenAI's GPT API**. Users can upload their resume in PDF or Word format and input a job description to create a customized cover letter in seconds.

## Features
- **Resume Parsing**: Extracts text from PDF and DOCX files using `PyMuPDF` and `python-docx`.
- **AI-Powered Generation**: Uses the `gpt-3.5-turbo` model from OpenAI to create a personalized cover letter.
- **User-Friendly Interface**: Built with Streamlit for an interactive experience.
- **Download Option**: Save the generated cover letter as a DOCX file.

## Requirements
Ensure you have Python installed, then install the required dependencies:
```bash
pip install streamlit openai pymupdf python-docx
