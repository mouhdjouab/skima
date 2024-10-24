# SkiMa - Job Matching Platform

SkiMa is web api that connects job seekers with employers through a smart matching algorithm based on skills, experience, and preferences. The platform features geolocation mapping of job postings, and JWT-based authentication for user security.

## Features
- **Job Matching Algorithm**: Recommends jobs to seekers based on skills and experience.
- **Geolocation**: Displays job locations using the MapQuest API.
- **User Profiles**: Separate profiles for job seekers and employers.
- **Secure Authentication**: JWT-based login for enhanced security.

## Tech Stack
- **Back-end**: Django REST Framework
- **Database**: PostgreSQL
- **Authentication**: JWT (JSON Web Tokens)
- **Geolocation**: MapQuest API

## Installation & Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/SkiMa.git
    cd SkiMa
    ```

2. Install dependencies

    **Back-end** (Django):
    ```bash
    cd backend
    pip install -r requirements.txt
    ```

3. Set up your environment variables for both front-end and back-end:
   - **Django**: Set environment variables for `DATABASE_URL`, `SECRET_KEY`, and `MAPQUEST_API_KEY`.

4. Run the development server:

    **Back-end**:
    ```bash
    python manage.py runserver
    ```

5. Visit `http://localhost:8000` for the back-end API.

## Usage

1. **Job Seekers**: Register, create a profile,  and get matched with jobs based on your skills.
2. **Employers**: Post job listings, search for candidates

## Next Steps
- Improve performance of the matching algorithm.

## License
This project is licensed under the MIT License.

