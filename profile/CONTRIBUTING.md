# Contributing to Sauti Salama

## Table of Contents
1. [Project Overview](#project-overview)
2. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
3. [How to Contribute](#how-to-contribute)
   - [Reporting Bugs](#reporting-bugs)
   - [Suggesting Features](#suggesting-features)
   - [Code Contributions](#code-contributions)
4. [Code of Conduct](#code-of-conduct)
5. [Style Guide](#style-guide)
   - [Python](#python)
   - [HTML/CSS](#htmlcss)
   - [JavaScript](#javascript)
6. [Submitting Issues](#submitting-issues)
7. [Submitting Pull Requests](#submitting-pull-requests)
8. [Community and Support](#community-and-support)
9. [License](#license)

## Project Overview

Sauti Salama aims to empower survivors of SGBV by providing them with the necessary tools and resources to report incidents and seek support. The platform ensures user safety, privacy, and accessibility across various devices and internet connection speeds. By leveraging modern technology, Sauti Salama strives to create a supportive environment for survivors, enabling them to access critical services and resources efficiently.

## Key Functionalities

### Anonymous Reporting
- **Feature**: Users can report SGBV incidents anonymously, with the option to include details if they choose.
- **Implementation**: A secure form that does not require personal identification information. The form allows users to describe the incident, select the type of violence, and provide any additional details they feel comfortable sharing.

### Access to Mental Health Support
- **Feature**: Users can connect with qualified mental health professionals.
- **Implementation**: A directory of mental health professionals is available, along with a booking system for appointments. Users can search for professionals based on their location, specialization, and availability.

### Access to Legal Guidance
- **Feature**: Lawyers are available to guide users on legal rights and processes.
- **Implementation**: A directory of pro bono lawyers is available, along with a system for scheduling legal consultations. Users can search for lawyers based on their expertise and availability.

### Access to Health Resources
- **Feature**: Users can access medical support and resources.
- **Implementation**: Information on nearby health facilities is provided, along with a booking system for medical appointments. Users can search for facilities based on their location and the type of medical support they need.

### Support Services Matching
- **Feature**: AI-driven matching of survivors with the best support services based on location and other criteria.
- **Implementation**: An AI model considers various factors such as location, survivor preferences, service provider specialties, and availability to provide accurate recommendations.

### Community Support
- **Feature**: Users can access a community of survivors, supporting each other as they heal.
- **Implementation**: A chat and forum system allows survivors to communicate and share experiences. Users can join discussion groups, participate in forums, and send private messages to other survivors.

### Analytics and Insights
- **Feature**: Administrators can view usage data and insights through a dashboard.
- **Implementation**: Real-time dashboards and advanced analytics tools provide detailed insights into platform usage, incident reports, and support service effectiveness.

### Campaigns and Advocacy
- **Feature**: Users can view ongoing campaigns and advocacy efforts, with details and participation options.
- **Implementation**: A dedicated page for campaigns and advocacy provides information on current initiatives, upcoming events, and ways to get involved.

### User Profile
- **Feature**: Users can view and edit their profile information.
- **Implementation**: A secure profile management system allows users to update their personal information, view their activity history, and manage their preferences.

### Settings
- **Feature**: Users can adjust notification preferences and privacy settings.
- **Implementation**: A settings page offers various customization options, including notification preferences, privacy settings, and account management.


## Getting Started

### Prerequisites
- Python 3.x
- Django
- WebSocket support (e.g., Django Channels)

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/salama.git
    cd salama
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run migrations:
    ```bash
    python manage.py migrate
    ```

4. Start the development server:
    ```bash
    python manage.py runserver
    ```
For the backend, navigate to [Backend](https://github.com/sautisalama/Salama)directory and follow the instructions in the `README.md` file.
For the frontend, navigate to the [Frontend Repo](https://github.com/sautisalama/Sauti) directory and follow the instructions in the `README.md` file.

## How to Contribute

### Reporting Bugs
If you find a bug, please report it by creating an issue on GitHub. Include as much detail as possible to help us understand and reproduce the issue.

### Suggesting Features
We welcome feature suggestions! Please create an issue on GitHub and describe the feature you would like to see.

### Code Contributions
1. Fork the repository.
2. Create a new branch for your feature or bugfix:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes.
4. Commit your changes with a descriptive commit message:
    ```bash
    git commit -m "Add feature: your feature description"
    ```
5. Push your changes to your fork:
    ```bash
    git push origin feature/your-feature-name
    ```
6. Create a pull request on the main repository.

## Code of Conduct

We expect all contributors to adhere to our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it to understand the standards of behavior we expect.

## Style Guide

### Python
- Follow PEP 8 guidelines.
- Use meaningful variable and function names.
- Write docstrings for all functions and classes.

### HTML/CSS
- Use semantic HTML5 elements.
- Follow BEM (Block Element Modifier) methodology for CSS class naming.

### JavaScript
- Use ES6+ features.
- Write comments to explain complex logic.

## Submitting Issues

When submitting an issue, please include:
- A clear and descriptive title.
- A detailed description of the problem.
- Steps to reproduce the issue.
- Any relevant screenshots or logs.

## Submitting Pull Requests

When submitting a pull request, please ensure:
- Your code follows the project's style guide.
- You have added tests for your changes.
- All tests pass.
- You have updated the documentation if necessary.

## Community and Support

Join our community on [WhatsApp]() for support and discussion. You can also reach out via [email](mailto:).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
