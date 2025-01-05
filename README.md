# ATS_resume_checker
ATS Resume Expert is a web application designed to help job seekers optimize their resumes for Applicant Tracking Systems (ATS). Built with Streamlit, Google Generative AI, and additional tools, this app provides comprehensive feedback on resumes by matching them against job descriptions.

🚀 Features
Resume Analysis: Upload your resume and receive detailed feedback on how well it aligns with a given job description.
Percentage Match: Get a percentage score indicating the match between your resume and the job description.
Strengths & Weaknesses: Identify areas where your resume excels and where it needs improvement.
Keyword Insights: Highlight missing keywords relevant to the job description.
🛠 Technologies Used
Streamlit: For building the interactive web interface.
Google Generative AI: Specifically the Gemini 1.5 Flash model for generating feedback.
pdf2image & Pillow (PIL): For handling and converting PDF resumes to images.
dotenv: For managing environment variables securely.
📦 Installation
Clone the Repository:
bash
Copy code
git clone https://github.com/yourusername/ats-resume-expert.git
Navigate to the Project Directory:
bash
Copy code
cd ats-resume-expert
Create a Virtual Environment (optional but recommended):
bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install Dependencies:
bash
Copy code
pip install -r requirements.txt
Set up the Environment Variables:
Create a .env file in the root directory.
Add your Google Generative AI API key:
makefile
Copy code
GOOGLE_API_KEY=your_google_api_key
🔧 Usage
Run the Streamlit App:
bash
Copy code
streamlit run app.py
Upload your resume (PDF format) and enter the job description.
Click on the buttons to get an evaluation or percentage match.
📚 How It Works
The app reads the uploaded PDF resume and converts the first page to an image.
It uses Google Generative AI to evaluate the resume against the provided job description.
The output includes a percentage match, keyword insights, and strengths/weaknesses.
🏗 Future Enhancements
More detailed feedback on each section of the resume.
Suggestions for skill improvements.
Integration with popular job boards for real-time feedback.
📝 License
This project is licensed under the MIT License. See the LICENSE file for details.

🤝 Contributions
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

📬 Contact
For any inquiries or feedback, please reach out at [your email].

