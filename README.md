
# 📄 ATS Resume Checker

ATS Resume Expert is a web application designed to help job seekers optimize their resumes for Applicant Tracking Systems (ATS). Built with Streamlit, Google Generative AI, and additional tools, this app provides comprehensive feedback on resumes by matching them against job descriptions.

## 🚀 Features:

- Resume Analysis: Upload your resume and receive detailed feedback on how well it aligns with a given job description.
- Percentage Match: Get a percentage score indicating the match between your resume and the job description.
- Strengths & Weaknesses: Identify areas where your resume excels and where it needs improvement.
- Keyword Insights: Highlight missing keywords relevant to the job description.

## 🛠 Technologies Used:

- Streamlit: For building the interactive web interface.
- Google Generative AI: Specifically the Gemini 1.5 Flash model for generating feedback.
- pdf2image & Pillow (PIL): For handling and converting PDF resumes to images.
- dotenv: For managing environment variables securely.

## 📦 Installation:

- Clone the Repository:
bash
Copy code

## 📦 Installation

Create a Virtual enviroment

```bash
  python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```
Install Dependencies:

```bash
  pip install -r requirements.txt
```

Set up the Environment Variables:
- Create a .env file in the root directory.
- Add your Google Generative AI API key:
```bash
  GOOGLE_API_KEY=your_google_api_key
```

## 🔧 Usage
  - Run the Streamlit App

```bash
  streamlit run app.py
```
- Upload your resume (PDF format) and enter the job description.
- Click on the buttons to get an evaluation or percentage match.

## 📚 How It Works
- The app reads the uploaded PDF resume and converts the first page to an image.
- It uses Google Generative AI to evaluate the resume against the provided job description.
- The output includes a percentage match, keyword insights, and strengths/weaknesses.

## 🏗 Future Enhancements
- More detailed feedback on each section of the resume.
- Suggestions for skill improvements.
- Integration with popular job boards for real-time feedback.


## 📝 License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/sumitx99/ATS-resume-checker/commit/5e2b01962a3777e54f5a1586704502694f5ee6a7) file for details.

## 📬 Contact

For any inquiries or feedback, please reach out at sumitranjan0304@gmail.com.
## Screenshots

![App Screenshot](https://i.ibb.co/ZHPvBMV/Screenshot-2025-01-06-130235.png[/img][/url])

