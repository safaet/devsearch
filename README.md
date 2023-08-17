# DevSearch

Welcome to DevSearch - Connecting Developers with Projects and Skills.

## Table of Contents


- [DevSearch](#devsearch)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [User Guide](#user-guide)
    - [Creating an Account](#creating-an-account)
    - [Adding Projects and Skills](#adding-projects-and-skills)
    - [Searching for Developers](#searching-for-developers)
  - [Technical Details](#technical-details)
    - [Technology Stack](#technology-stack)
    - [Directory Structure](#directory-structure)
  - [Contributing](#contributing)
  - [Contributing](#contributing-1)
    - [Code Style](#code-style)
    - [Bug Reports and Feature Requests](#bug-reports-and-feature-requests)
    - [Testing](#testing)
    - [Code Review](#code-review)
  - [License](#license)



## Introduction

DevSearch is a web application built using the Django framework, Python, JavaScript, HTML, and CSS. Its primary purpose is to provide a platform where developers can create accounts, showcase their projects and skills, and allow other users to search and discover developers based on their preferences.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Python (version 3.5)
- Django (version 3.0)

### Installation

1. Clone this repository to your local machine:
`git clone https://github.com/safaet/devsearch.git`

2. Navigate to the project directory:
- `cd devsearch`

3. Install the required dependencies:

 - `pip install -r requirements.txt`


4. Apply database migrations:
 - `python manage.py migrate`


5. Start the development server:

- `python manage.py runserver`


6. Access the application in your web browser at `http://127.0.0.1:8000/`.

## User Guide

### Creating an Account

1. Navigate to the registration page.
2. Fill in your details, including username, email, and password.
3. Click the "Sign Up" button to create your account.

### Adding Projects and Skills

1. Log in to your account.
2. Go to your profile dashboard.
3. Click on the "Add Project" button to showcase your projects.
4. Provide project details, including the title, description, and relevant links.
5. To add skills, navigate to the "Edit Profile" section.
6. Add skills by clicking the "Add Skill" button and entering skill details.

### Searching for Developers

1. On the homepage, use the search bar to enter your preferred skills or project keywords.
2. Browse through the list of developers who match your search criteria.
3. Click on a developer's profile to view their projects and skills.

## Technical Details

### Technology Stack

- Django (Python web framework)
- HTML/CSS (Frontend styling)
- JavaScript (Frontend interactivity)

### Directory Structure


devsearch/
|-- manage.py
|-- devsearch/
| |-- settings.py
| |-- urls.py
| |-- ...
|-- profiles/
| |-- models.py
| |-- views.py
| |-- templates/
| | |-- profile.html
| | |-- ...
|-- projects/
| |-- models.py
| |-- views.py
| |-- templates/
| | |-- project.html
| | |-- ...
|-- static/
| |-- css/
| |-- js/
| |-- ...
|-- templates/
| |-- base.html
| |-- ...
|-- requirements.txt
|-- README.md



## Contributing

## Contributing

We appreciate contributions from the community that can help improve DevSearch. If you're interested in contributing, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`.
3. Make your changes and test thoroughly.
4. Commit your changes with descriptive commit messages.
5. Push your changes to your forked repository.
6. Create a pull request (PR) to the `main` branch of this repository.
7. Provide a detailed description of your changes in the PR.
8. Ensure your code follows our coding conventions and standards.

### Code Style

- Follow the [PEP 8](https://www.python.org/dev/peps/pep-0008/) style guide for Python code.
- Use meaningful variable and function names that describe their purpose.
- Keep your code well-documented using comments and docstrings.

### Bug Reports and Feature Requests

If you encounter a bug or have an idea for a new feature, please submit an issue on the GitHub repository. Make sure to provide detailed steps to reproduce the bug and include any relevant information.

### Testing

Ensure that your changes are thoroughly tested. Write unit tests for new features and ensure that existing tests are not broken. Make sure the test suite passes before submitting a pull request.

### Code Review

All pull requests will be reviewed by the project maintainers. Constructive feedback will be provided if necessary. Be prepared to make adjustments to your code based on the feedback received.

By contributing to DevSearch, you agree that your contributions will be licensed under the same license as this project.

Thank you for contributing and helping make DevSearch better for everyone!


## License

DevSearch is open-source software released under the [MIT License](https://opensource.org/licenses/MIT).

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


---

This concludes the DevSearch documentation. If you have any further questions or need assistance, please don't hesitate to contact our support team. Happy coding!

