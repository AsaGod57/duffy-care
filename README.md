# Duffy Care

**Tag Line**: Delivering healthcare at your desktop

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Architecture](#architecture)
- [APIs](#apis)
- [Data Model](#data-model)
- [User Stories](#user-stories)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Challenges](#challenges)
- [Collaboration](#collaboration)
- [Project Updates](#project-updates)
- [Progress](#progress)
- [License](#license)

## Project Overview

Duffy Care is a platform designed to connect elderly people with healthcare providers for homecare services. The platform focuses on delivering healthcare directly to the doorstep of the aged in society.

## Features

- User authentication and role-based access control
- Posting and browsing of healthcare job listings
- Secure data handling and storage
- Integration with healthcare APIs for interoperability
- User-friendly interface with accessibility considerations for elderly users

## Technologies Used

- **Frontend**: React.js, TailwindCSS
- **Backend**: Node.js, Express.js, MongoDB
- **Deployment & Version Control**: Docker, AWS, GitHub

## Architecture

The system architecture centers around a React.js frontend, communicating with a Node.js/Express backend, with data persistence handled by MongoDB. AWS serves as the deployment environment, ensuring scalability and reliability.

## APIs

- **/api/carejobs**
  - `GET`: Fetches a list of care jobs.
  - `POST`: Submits a new care job listing.

- **/api/apply**
  - `POST`: Allows users (healthcare service providers) to apply for jobs.

## Data Model

The data model includes three primary entities: Users, Jobs, and Applications. Relationships are defined to facilitate easy retrieval of job applications per user (Healthcare Service Provider) and listings per employer (Care Seeker).

## User Stories

- As a healthcare service provider, I want to view job listings so that I can find care job opportunities that match my skills.
- As an employer (care seeker), I want to post care job opportunities so that I can find skilled healthcare service providers from the community.
- As a healthcare provider, I want a hassle-free search for care job opportunities with competitive salaries.

## Setup and Installation

### Prerequisites

- Node.js
- npm
- Docker (optional for containerization)
- AWS account (for deployment)

### Frontend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/AsaGod57/duffy-care.git
   cd duffy-care/frontend
