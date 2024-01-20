# ATS Using Gemini Pro API

## Overview

This project is an End-to-End Resume Application Tracking System (ATS) using the Google Gemini Pro Vision LIM Model. Resumes are processed through a Streamlit web application available at [ats-llm-gemini.streamlit.app](https://ats-llm-gemini.streamlit.app/).

## Requirements

- Python 3.x
- Install dependencies using:

  ```bash
  pip install -r requirements.txt

## Configuration

1. **Create a `.env` file in the project root directory and add the API key:**

    ```env
    GEMINI_PRO_API_KEY=your-api-key
    ```
   
    Replace `your-api-key` with the actual API key obtained from the Gemini Pro Vision API.

## Usage

1. **Run the Streamlit app:**

    ```bash
    streamlit run app.py
    ```

2. **Visit [ats-llm-gemini.streamlit.app](https://ats-llm-gemini.streamlit.app/) in your browser to access the application.**

3. **Upload resumes through the web interface, and the Gemini Pro Vision LIM Model will process and parse them.**

