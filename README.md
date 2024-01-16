# GPTs-Powered-Job-Tracker

## Introduction

Welcome to the repository of Job Tracker AI, a innovative approach to job application management. This application greatly simplified the way users interact with and maintaining job application data by replacing a conventional frontend with a ChatGPT-based AI interface, Job Tracker AI. It offers a unique, conversational experience for tracking and managing job applications, backed by a robust AWS cloud infrastructure.

## Features

- **ChatGPT-based Interaction:** Interact with the Job Tracker through intuitive, conversational AI, making the management of job applications more engaging and user-friendly.
- **Comprehensive Tracking:** Track job applications' status, company details, application dates, and more.
- **Real-time Updates:** Stay informed with the latest status of your job applications in real-time.
- **Scalable Cloud Backend:** Powered by AWS services including Lambda, RDS, and API Gateway for high reliability and scalability.

## Architecture

- **Frontend:** ChatGPT-based AI (Job Tracker AI).
- **Backend:**
  - **AWS API Gateway:** Routes API requests to appropriate Lambda functions.
  - **AWS Lambda:** Six Lambda functions in Python, each for a specific API endpoint.
  - **AWS RDS (MySQL):** Stores job application data.

## Getting Started

### Prerequisites

- AWS account with Lambda, RDS, and API Gateway.
- Basic understanding of Python and SQL.

### Installation

1. Clone the repository
2. Set up AWS services as per the architecture.
3. Configure Lambda functions with the provided code in the `lambda/` directory.
4. Initialize the RDS MySQL database using the schema in `schema.sql`.

### Configuration

- Update the `.env` file with your AWS credentials and database connection details.
- Adjust the API Gateway settings according to your preference.

## Usage

Interact with the Job Tracker AI through the provided interface. Example commands include:

- "Show me the status of my applications to Google."
- "Update the status of my application for the Software Engineer role at Amazon to 'Interviewing'."
