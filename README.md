AI-Based Skill Gap Analysis & Career Readiness Platform 

Overview of the platform :
This project is an AI-based Skill Gap Analysis and Career Readiness System developed to help students understand their current skill level, identify missing skills, and prepare for industry requirements.

The system also includes aptitude tests, technical MCQs, and career trend guidance.

The application is built using Python and Streamlit, with logic based evaluation and optional AI integration for future expansion.


Key Features :

1. User Authentication

First time users can sign up using a username and password.
Existing users can log in using their credentials.
Login session is maintained until logout.
Only one signup is allowed initially to avoid multiple dummy users.

2. Skill Gap Analysis (Core Feature)

The system compares a student’s existing skills with industry-= required skills.

Skill Gap Logic

Each role has predefined required skills.

Skill Gap Percentage Formula: (Number of Missing Skills / Total Required Skills) × 100

Example Skill Mapping

Anu – Cloud Developer
Required Skills: AWS, Cloud Computing, DevOps
Available Skills: AWS, Cloud Computing, DevOps
Skill Gap: 0%

Ram – Frontend Developer
Required Skills: HTML, CSS, React
Available Skills: HTML, CSS, React
Skill Gap: 0%

Uma – Machine Learning Engineer
Required Skills: Python, Machine Learning, TensorFlow
Available Skills: Python, Machine Learning
Skill Gap: 33%

Sita – Data Analyst
Required Skills: Python, Pandas, Statistics
Available Skills: Python, Statistics
Skill Gap: 33%

Radha – Cybersecurity Analyst
Required Skills: Linux, Network Security, Ethical Hacking
Available Skills: Linux, Network Security
Skill Gap: 33%

The skill gap is displayed visually using a bar chart.

3. Aptitude Test Module
Contains 10 predefined aptitude questions.
Questions are displayed with options using radio buttons.
After submission: 
The total score is displayed.

4. Technical MCQ Test
Contains 10 technical multiple-choice questions.
Covers programming and computer fundamentals.
System validates and calculates score after submission.
Result is shown clearly with score.

5. Dashboard View
The dashboard shows:
Skill Gap Graph 
Aptitude Test Score
Technical MCQ Score

This gives a complete performance overview of the student.

6. Career Trend Section
The system also displays trending career paths such as:
Artificial Intelligence & Machine Learning
Data Science & Analytics
Cloud Computing
Cybersecurity
Full Stack Development

This helps students understand industry demand and plan learning paths.

7. Logout and Session Control
Users can log out safely.
After logout, login screen is shown again.
Session data is cleared properly.

Technologies Used:
⦁	Python
⦁	Streamlit
⦁	Pandas
⦁	Matplotlib
⦁	Basic Authentication (Local Session Based)


Running the Project:

1.Install dependencies

pip install streamlit pandas matplotlib

2.Run the application

streamlit run app.py

3.Open the URL shown in the terminal 

Conclusion
 
This project demonstrates:
       Real-time skill gap analysis
       Interactive assessment system
       Clear performance evaluation
       Simple, scalable design
