# Capacity Connect

## Project Overview

Capacity Connect is a digital capacity-building and learning management portal designed for the Ministry of Earth Sciences (MoES). It supports organizational training, competency development, knowledge sharing, and learning activities across meteorological and related scientific domains.

The portal aims to bring training resources, learning activities, and capacity-building information together in one centralized platform.

## Features

- Role-based access for Trainees, Trainers, and Administrators.
- Dashboard to view relevant learning and training information.
- Centralized learning and capacity-building resources.
- Training and competency development support.
- Knowledge sharing among organizational users.
- Support for domains such as Weather Forecasting, Radar Operations, Satellite Meteorology, Climate Science, and Disaster Management.
- Responsive and user-friendly interface.
- Centralized portal concept for HQ, Regional Meteorological Centres (RMCs), Meteorological Centres (MCs), and observatories.

## Technologies Used

- React
- JavaScript / TypeScript (depending on the implementation)
- HTML
- CSS
- Vite
- Python
- FastAPI
- Uvicorn

## Project Structure

```text
CAPACITY CONNECT PROJECT/
├── package.json
├── index.html
├── src/
│   ├── App.*
│   ├── main.*
│   └── components/
├── public/
├── requirements.txt
└── README.md
```

*Note: The exact files and folders may vary depending on the current implementation.*

## Installation

### 1. Install Node.js

Install Node.js and make sure Node.js and npm are available on your system.

### 2. Open the project folder

Open the Capacity Connect project folder in Visual Studio Code.

### 3. Install frontend dependencies

Open the VS Code terminal and run:

```bash
npm install
```

### 4. Run the frontend application

Run the following command:

```bash
npm run dev
```

### 5. Open the website

Open the local address in your browser:

http://localhost:3000

## Backend

The backend can be developed or run separately using FastAPI and Uvicorn, depending on the available backend implementation.

Install backend dependencies using:

```bash
py -m pip install -r requirements.txt
```

Run the backend using the appropriate FastAPI application command configured in the project.

## How to Use

1. Open the Capacity Connect website.
2. Explore the portal dashboard and available navigation options.
3. Access the relevant sections based on the available user role.
4. Explore learning resources and capacity-building features implemented in the application.

## Important Notes

- Keep the frontend terminal running while using the local website.
- The local development URL is accessible on your computer while the server is running.
- Backend-dependent features require the backend to be configured and running.
- The available features depend on the current implementation.
- Do not commit API keys, passwords, or other confidential information to a public repository.

## Project Details

**Project:** Capacity Connect  
**Problem Statement:** SIH26075  
**Organization:** Ministry of Earth Sciences (MoES)  
**Purpose:** Digital Capacity Building and Learning Management Portal
