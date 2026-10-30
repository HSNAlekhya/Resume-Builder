# AI Resume-Builder

# SmartResume AI — Real-Time Resume Builder & ATS Analyzer

      SmartResume AI is a full-stack web application that helps users create professional resumes, analyze their resumes for Applicant Tracking System (ATS) compatibility, and improve their chances of getting shortlisted.
      The application provides a real-time resume preview, resume management, and PDF downloads through a user-friendly interface.

## Features

- **Real-Time Resume Builder:** Create and edit resumes with an instant preview.
- **ATS Resume Analyzer:** Analyze resumes and generate an ATS compatibility score.
- **User Authentication:** Register and log in securely.
- **Resume Management:** Save, update, and manage resumes.
- **PDF Download:** Download resumes in PDF format.
- **Responsive Design:** Access the application on desktops, tablets, and mobile devices.

## Tech Stack

**Frontend**
- React.js
- HTML5
- CSS3
- JavaScript

**Backend**
- Python
- Django
- Django REST Framework

**Database**
- SQLite for initial development
- PostgreSQL for future deployment

**Tools**
- Visual Studio Code
- Git and GitHub
- npm

## Project Structure

```text
SmartResume-AI/
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
├── backend/
│   ├── manage.py
│   ├── requirements.txt
│   └── ...
├── .gitignore
└── README.md
```

*Note: The folder structure may vary depending on your implementation.*

## Installation and Setup

### Prerequisites

Install the following before running the project:

- Python 3.x
- Node.js and npm
- Visual Studio Code
- Git

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd SmartResume-AI
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### 2. Set Up the Backend

Open a terminal in VS Code and navigate to the backend directory.

```bash
cd backend
python -m venv venv
```

Activate the virtual environment.

**Windows:**
```bash
venv\Scripts\activate
```

Install the backend dependencies.

```bash
pip install -r requirements.txt
```

Apply database migrations.

```bash
python manage.py migrate
```

Start the Django development server.

```bash
python manage.py runserver
```

Backend URL: `http://127.0.0.1:8000/`

### 3. Set Up the Frontend

Open a second terminal in VS Code.

```bash
cd frontend
npm install
npm start
```

If the project uses Vite instead of Create React App, run:

```bash
npm run dev
```

Frontend URL: Check the local URL displayed in your terminal, usually `http://localhost:3000/` or `http://localhost:5173/`.

## How It Works

1. Users register or log in to the application.
2. Users enter their personal details, education, skills, projects, and work experience.
3. The application generates a resume with a real-time preview.
4. Users analyze their resume to check ATS compatibility.
5. Users review the analysis and improve their resume content.
6. Users save their resumes and download the final version as a PDF.

## Future Enhancements

- AI-powered resume content suggestions.
- Job description matching and keyword analysis.
- Multiple professional resume templates.
- Cloud-based resume storage.
- Deployment with a production database.
- Integration with job portals and career platforms.

## Learning Outcomes

This project demonstrates practical knowledge of full-stack web development, React.js, Python, Django REST APIs, database integration, user authentication, RESTful communication, and document generation.

## Project Status

**In Development** — Features and implementation details may change as development progresses.

## Author

Developed as a full-stack portfolio project to demonstrate frontend development, backend API development, database management, and resume optimization concepts.

## License

This project is intended for educational and portfolio purposes. A license can be added when the project is published.
