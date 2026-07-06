# Student-Flow

Student productivity & job application tracker — track modules, deadlines, revision plans, job applications, interview prep, and notes in one place.

## About

Student-Flow is a full-stack web app built as a summer project between my second and third year of a Computer Science degree. It's designed to help students manage the chaos of final-year in one place — bringing together module tracking, deadline management, revision planning, job applications, and interview preparation into a single, simple dashboard. Instead of juggling five different apps and a stack of sticky notes, everything lives in one spot.

This version (v1) is built with Python and Flask, without a frontend framework, as a way to get comfortable with the fundamentals of full-stack development before introducing React in v2.

## Features

- **Module tracker** – keep track of your modules and coursework in one place
- **Deadline manager** – add, edit, and remove deadlines so nothing slips through the cracks
- **Revision planner** – plan out revision sessions ahead of exams
- **Job application tracker** – log job applications and their current status
- **Interview prep notes** – keep prep notes and materials organised per application
- **General notes** – a simple space for anything else worth remembering

## Tech Stack

- **Backend:** Python, Flask
- **Database:** SQLite
- **Frontend:** HTML, Jinja2 templating, CSS
- **Version control:** Git & GitHub

## Project Structure

```
student-flow/
├── app/
│   ├── templates/       # Jinja2 HTML templates
│   ├── static/           # CSS, JS, images
│   ├── models.py         # Database models
│   ├── routes.py         # Flask routes
│   └── __init__.py
├── tests/                # Automated tests
├── requirements.txt      # Python dependencies
├── run.py                # App entry point
└── README.md
```

*(Structure will be updated as the project develops.)*

## Getting Started

### Prerequisites

- Python 3.10+
- pip

### Setup

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/student-flow.git
   cd student-flow
   ```

2. Create and activate a virtual environment
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

4. Run the app
   ```bash
   python run.py
   ```

5. Open your browser and go to `http://127.0.0.1:5000`

## Screenshots

*(To be added once the UI is built.)*

## Roadmap

- [ ] Build v1 as a Flask app with SQLite and Jinja2 templates
- [ ] Deploy v1 online
- [ ] Learn React fundamentals (components, state, props, hooks)
- [ ] Rebuild the frontend in v2 using React
- [ ] Add user authentication so multiple students can use the app
- [ ] Add data visualisation for deadlines and application progress

## What I Learned

*(To be filled in once v1 is complete — a short reflection on the backend, frontend, and any challenges along the way.)*

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

Built by Thomas Nunn as a summer project, second → third year Computer Science.

