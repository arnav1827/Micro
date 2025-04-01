**Edvaan** is an advanced educational platform designed to enhance learning experiences through AI-driven insights, gamified learning, and blockchain-based achievement recognition. It integrates modern technology to provide personalized learning pathways, performance tracking, and monetized test series for students preparing for various competitive exams.

**Problem Statement**
Traditional e-learning platforms often lack personalized feedback, engagement, and real-time performance analysis. Many learners struggle with:

Inconsistent progress tracking – No proper performance analytics to identify weak areas.

Lack of motivation – Absence of gamification and incentives for continuous learning.

Scattered learning resources – Students must navigate multiple platforms for books, test series, and research materials.

No verifiable achievements – Certifications and accomplishments lack credibility in digital spaces.

**Key Features & Benefits**
✅ AI-Powered Assistance – A chatbot for instant doubt resolution and personalized guidance.
✅ Performance Dashboards – Real-time analytics to track progress and identify weaknesses.
✅ Comprehensive Test Series – Past and latest test series with detailed solutions and time integration.
✅ Curated Learning Resources – Access to recommended books, research papers, and study materials.
✅ Centralized & Decentralized Storage – Efficient database model combining MongoDB (for general use) and Ethereum-based blockchain (for NFT-based achievements).

**Dependencies**
Below is a list of all the required libraries and packages for running the Edvaan project. Make sure to install them using the requirements.txt file.

six==1.16.0
pillow==8.4.0
openai==0.27.0
gTTS==2.2.3
pyCaret==2.3.3
pytz==2021.1
djangorestframework==3.12.4
djongo==1.3.6
celery==5.1.2
redis==3.5.3

**Setup Instructions**

To set up and run the Edvaan project, follow these steps:

1.Clone the Repository
  Clone the repository to your local machine:
  
  git clone https://github.com/yourusername/Micro.git
  cd CodeForge/Edvaan

2.Install Dependencies
  Install all required Python dependencies listed in requirements.txt:
  
  pip install -r requirements.txt

3.Start the Development Server
  Run the Django development server:
  python manage.py runserver

4.Access the Application
  You can access the platform at:
  http://127.0.0.1:8000
