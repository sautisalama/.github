# Contributing to Sauti Salama

Sauti Salama ("Safe Voice" in Swahili) is a digital platform designed to provide critical services to survivors of sexual and gender-based violence (SGBV) in Kenya. The platform includes a mobile progressive web application (PWA) and a USSD service, offering a safe, anonymous, and accessible channel for survivors to report incidents and access legal, medical, and mental health support.

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

### Key Features
- Real-time chat functionality
- User authentication and management
- Responsive design for various screen sizes

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
