# Project Structure

This document provides an overview of the project's file and folder structure. Each part of the application is organized according to the **Service-Controller-Repository** architectural pattern for better maintainability, modularity, and scalability.

## 📁 Project Tree

```plaintext
.
├── alembic/               # [Alembic] Database migration scripts 
├── config/                # [API] App configuration
├── controllers/           # [API] API endpoints and HTTP route handlers (Controller Layer)
├── docs/                  # Documentation files
├── dtos/                  # [API] Data Transfer Objects for request/response schemas
├── models/                # [API & Alembic] Database models and ORM classes (Model Layer)
├── repositories/          # [API] Data access logic and database interaction (Repository Layer)
├── services/              # [API] Business logic layer (Service Layer)
├── .env                   # Environment variables (e.g., database credentials)
├── .gitignore             # Specifies intentionally untracked files to ignore
├── alembic.ini            # Alembic configuration file
├── dockerfile             # Docker image instructions to build the app container
├── utils.py               # Utils
├── main.py                # FastAPI entry point (starts the app)
├── README.md              # Project documentation 
├── requirements.txt       # Python dependencies list for pip installation

````
