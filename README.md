# alx_travel_app

A Django-based travel listing platform, serving as the foundation for a scalable, production-ready backend. This project is part of a multi-stage learning experience and will be expanded with more features in future milestones.

## Milestone 1: Setup and Database Configuration

### Overview

This milestone focuses on setting up the initial project structure, configuring a robust MySQL database, and integrating essential tools for API documentation and maintainable configurations. The goal is to establish best practices for Django project initialization and prepare the application for future development.

### Key Objectives

- **Project Initialization:**  
  - Create a Django project named `alx_travel_app`.
  - Add an app named `listings` for core functionalities.

- **Dependency Management:**  
  - Install and configure the following packages:
    - `django`
    - `djangorestframework`
    - `django-cors-headers`
    - `drf-yasg` (Swagger API documentation)
    - `celery` and `rabbitmq` (for future background tasks)

- **Settings Configuration:**  
  - Use `django-environ` to manage environment variables securely via a `.env` file.
  - Configure MySQL as the primary database, with credentials loaded from environment variables.
  - Set up Django REST Framework and CORS headers.

- **Swagger Integration:**  
  - Integrate Swagger using `drf-yasg` to automatically document all APIs.
  - Make API documentation accessible at `/swagger/`.

- **Version Control:**  
  - Initialize a Git repository.
  - Commit all setup files and push to a GitHub repository named `alx_travel_app`.

### Project Structure

```
alx_travel_app/
├── listings/
├── alx_travel_app/
│   ├── settings.py
│   ├── urls.py
├── requirements.txt
├── .env
└── README.md
```

### Tasks Checklist

- [ ] Initialize Django project and `listings` app
- [ ] Install all required dependencies
- [ ] Configure MySQL database using environment variables
- [ ] Set up Django REST Framework and CORS headers
- [ ] Integrate Swagger documentation at `/swagger/`
- [ ] Initialize Git repository and make initial commit

---

**Note:**  
This is the first milestone. The project will be expanded in future stages to add more features and functionalities.
