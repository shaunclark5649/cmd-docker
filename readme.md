# Contractor Management System

## Overview

This repository provides instructions for setting up the Contractor Management System, including the frontend and backend components. The system uses Docker for containerization.

## Getting Started

### Prerequisites

- Docker
- Docker Compose

### Setup Instructions

1. **Clone Repositories**

   Clone the frontend and backend repositories into their respective folders:

```bash
   git clone git@github.com:shaunclark5649/cms-fe.git frontend
   git clone git@github.com:shaunclark5649/cms-be.git backend
```

2. **Clone the Docker Compose configuration repository:**

```bash
   git clone git@github.com:shaunclark5649/cms-docker.git
```

3.  **Clone the Docker Compose configuration repository:**

```bash
  docker-compose --build
```

## Project Structure

- `frontend/` - Contains the frontend application code, built with Vite, React, and TypeScript.
- `backend/` - Contains the backend API code, built with Express.js and TypeScript.
- `docker-compose.yml` - Docker Compose configuration file for orchestrating the frontend and backend services.