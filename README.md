# URL Shortener - A Full-Stack Application

![URL Shortener](https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80)

A modern URL shortener application built with React, Tailwind CSS, and Spring Boot that allows users to convert long URLs into shorter, more manageable links.

## Live Demo

Check out the live application: [URL Shortener Demo](https://ornate-clafoutis-1c2c08.netlify.app/)

## Features

- **URL Shortening**: Convert long URLs into short, shareable links
- **Custom Aliases**: Option to create custom short URLs
- **Analytics**: Track click counts and usage statistics
- **Responsive Design**: Works on all device sizes
- **User-Friendly Interface**: Clean and intuitive UI
- **Secure**: HTTPS support for all shortened links

## Technologies Used

### Frontend
- React.js
- Tailwind CSS
- Axios for API calls
- React Router for navigation
- React Icons for beautiful icons

### Backend
- Spring Boot
- Spring Security (if implemented)
- Hibernate/JPA
- MySQL/PostgreSQL (or your chosen database)
- JUnit for testing

## Installation

### Frontend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/kartikeygit11/Url_Shortner_SB.git
   cd Url_Shortner_SB/frontend
   Url_Shortner_SB/

   

```text
Url_Shortner_SB/
├── frontend/               # React frontend
│   ├── public/            # Static files
│   ├── src/               # React source code
│   │   ├── components/    # Reusable components
│   │   ├── pages/         # Page components
│   │   ├── services/      # API services
│   │   ├── utils/        # Utility functions
│   │   ├── App.js        # Main app component
│   │   └── index.js      # Entry point
│   └── package.json      # Frontend dependencies
│
├── backend/               # Spring Boot backend
│   ├── src/main/java/     # Java source code
│   │   ├── controller/    # REST controllers
│   │   ├── model/         # Data models
│   │   ├── repository/    # Data repositories
│   │   ├── service/       # Business logic
│   │   └── config/        # Configuration classes
│   ├── src/main/resources # Resources
│   │   └── application.properties # Configuration
│   └── pom.xml           # Backend dependencies
└── README.md             # Project documentation
## API Endpoints

| Endpoint              | Method | Description                |
|-----------------------|--------|----------------------------|
| `/api/shorten`        | POST   | Create a short URL         |
| `/api/urls`           | GET    | Get all URLs              |
| `/api/urls/{id}`      | GET    | Get URL by ID             |
| `/api/urls/{alias}`   | GET    | Get URL by alias          |
| `/api/urls/{id}`      | DELETE | Delete a URL              |
