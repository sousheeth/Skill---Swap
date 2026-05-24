# Skill---Swap
A Peer-to-Peer Colloborative Learning Platform Built with Django.
A secure, web-based full-stack application built using Python and Django that enables users to exchange diverse skills, manage interactive profiles, and communicate through mutual learning frameworks. 

## Technical Architecture
* **Backend Framework:** Python / Django (MVC Architecture)
* **Database:** PostgreSQL / Django ORM
* **Security Layer:** CSRF Tokens, Django Native User Authentication, Session State Management
* **Communication:** Real-Time Internal Messaging Engine & Automated Mail Routing (`send_mail`)

## Core Implementations
* **Relational Schema:** Configured complex database interactions utilizing `ForeignKey` and `OneToOneField` mappings to cleanly link profiles, feedback ratings, messages, and requests.
* **Algorithmic Search:** Engineered a keyword-matching profile query parser supporting comma-separated inputs for fast profile discovery.
* **Data Validation:** Developed comprehensive backend validation routines using the Django messages framework to safeguard against silent failures and malicious inputs.

## Setup & Installation
1. Clone the repository:
git clone https://github.com/sousheeth/Skill-Swap.git

2. Install dependencies:
pip install -r requirements.txt

3. Apply database migrations:
python manage.py migrate

4. Run server:
python manage.py runserver
