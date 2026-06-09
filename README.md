# Placement Tracker

A full-stack web application built to track DSA problem-solving progress for placement preparation.

## Features

* Add new problems
* View all solved problems
* Update problem difficulty
* Delete problems
* Search problems by topic
* Filter problems by difficulty
* Dashboard analytics

  * Total Problems Solved
  * Easy Problems
  * Medium Problems
  * Hard Problems

## Tech Stack

### Frontend

* React
* Vite
* JavaScript
* CSS

### Backend

* FastAPI
* Python

### Database

* MySQL

## Project Architecture

React Frontend → FastAPI Backend → MySQL Database

## API Endpoints

### Get All Problems

```http
GET /problems
```

### Get Problem By ID

```http
GET /problems/{id}
```

### Search Problems

```http
GET /problems/search
```

### Add Problem

```http
POST /problems
```

### Update Problem

```http
PUT /problems/{id}
```

### Delete Problem

```http
DELETE /problems/{id}
```

## Concepts Used

### React

* Components
* Props
* useState
* useEffect
* Event Handling
* Array Mapping
* Filtering Data
* API Integration

### FastAPI

* REST APIs
* Pydantic Validation
* CRUD Operations
* Query Parameters
* Path Parameters

### Database

* MySQL Integration
* SQL Queries
* Search and Filtering

## What I Learned

* Building full-stack applications
* Creating REST APIs using FastAPI
* Connecting React frontend with backend services
* Managing state using React Hooks
* Working with MySQL databases
* Using Git and GitHub for version control
* Deploying React applications using GitHub Pages

## Future Improvements

* User Authentication
* Progress Charts
* Daily Streak Tracking
* Cloud Database Deployment
* Notes for Problems

## Author

**Syed Zain Ahmed**

GitHub: https://github.com/ZAIN6607

LinkedIn: https://www.linkedin.com/in/syed-zain-ahmed-a78152325
