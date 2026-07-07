# Employee Wellness Management Analytics

## Project Objective

**Employee Wellness Management Analytics** is an AI-powered Employee Wellness Management System designed to help users securely register, log in, upload employee wellness datasets, and analyze wellness-related data.

The application is developed using **Streamlit**, **PostgreSQL (Neon Database)**, and **JWT Authentication**. The project is developed and tested using **Google Colab** and can be accessed through an **ngrok public URL**. Deployment support using **Hugging Face Spaces** is also planned.

## Technologies Used

* Python
* Streamlit
* PostgreSQL (Neon Database)
* JWT (JSON Web Token) Authentication
* Google Colab
* Hugging Face Spaces
* ngrok

## Google Colab Setup Instructions

1. Open the `Authentication.ipynb` notebook in Google Colab.

2. Add the following required Secrets:

   * `DB_HOST`
   * `DB_PORT`
   * `DB_NAME`
   * `DB_USER`
   * `DB_PASSWORD`
   * `JWT_SECRET`
   * `SMTP_EMAIL`
   * `SMTP_APP_PASSWORD`
   * `NGROK_AUTHTOKEN`

3. Enable notebook access for all Secrets.

4. Run all notebook cells in order.

5. Wait for the Streamlit application to start.

6. Open the generated ngrok public URL.

7. Register a new account or log in using an existing account.

8. After successful authentication, access the application Dashboard.

## Project Structure

```text
Employee-Wellness-Management-Analytics/
│
├── README.md
│
└── Milestone1/
    ├── Authentication.ipynb
    ├── README.md
    └── screenshots/
        ├── home_page.png
        ├── signup_page.png
        ├── login_page.png
        ├── forgot_password_page.png
        ├── dashboard.png
        └── neon_database.png
```

## Security

Sensitive credentials and secrets are not stored directly in the source code or uploaded to GitHub.

Database credentials, JWT secrets, SMTP credentials, and ngrok authentication tokens should be securely stored using Google Colab Secrets or environment variables.

## Author

**Soham Pal**

B.Tech in Computer Science and Engineering
Adamas University

## Project Status

🚧 **Project Under Development**

**Milestone 1:** User Authentication Module

