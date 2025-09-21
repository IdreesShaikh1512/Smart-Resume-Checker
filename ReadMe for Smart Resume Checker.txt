ReadMe for Smart Resume Checker

Problem Statement:

Manual resume checking presents several challenges that hinder both recruiters and job seekers. First, it is extremely time-consuming, as reviewing large volumes of resumes requires significant human effort. This leads to delays in the hiring process and makes it difficult to scale for situations such as campus placements or mass recruitment drives. Additionally, the process is costly, as organizations need to allocate resources and personnel to manually evaluate resumes.

Another major issue is the subjectivity and inconsistency of feedback. Different reviewers may interpret resumes differently, resulting in varied evaluations that can confuse candidates. Human reviewers are also prone to biases and may overlook critical details such as role-specific keywords or formatting issues that are crucial for Applicant Tracking Systems (ATS). Furthermore, manual reviews often lack domain-specific feedback, as recruiters may not always provide insights tailored to particular job roles. Combined with delayed feedback, these limitations prevent candidates from improving their resumes in time, reducing their chances of success.



Technologies used:

The Smart Resume Checker has been built using a mix of simple yet powerful technologies. At its core, it runs on Python, which takes care of the main processing and logic. For the user interface, we used Streamlit, which makes it easy for anyone to upload their resume and instantly see the results on a clean, interactive dashboard.

When a resume is uploaded, tools like PyPDF2 and python-docx help in reading and extracting the information from PDF or Word files. To actually understand the text, we rely on natural language processing (NLP) libraries such as spaCy and NLTK, which help the system identify important keywords, skills, and areas for improvement. Data handling and analysis are managed using Pandas, while clear and engaging visualizations are created with libraries like Plotly. We also use supporting tools like Poppler for PDF handling and provide options to export results into Excel for easy sharing. Altogether, these technologies work hand in hand to give users a smooth, accurate, and helpful experience.



Steps to run it:

git clone https://github.com/IdreesShaikh1512/Smart-Resume-Checker
cd Smart-AI-Resume-Analyzer(incase if it shows error then ignore this line)

python -m venv venv
venv\Scripts\activate(windows)
source venv/bin/activate(mac)

pip install -r requirements.txt

python -m spacy download en_core_web_sm( TO download spaCy model)

streamlit run app.py

IT SHOULD RUN AND SHOULD DIRECLTY OPEN OUR WEBSITE ON YOUR BROWSER


