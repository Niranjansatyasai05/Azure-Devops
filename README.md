# Python CI/CD Pipeline using Azure DevOps

## Overview

This project demonstrates a Python Continuous Integration pipeline using
Azure DevOps and YAML.

The pipeline automatically:

- Installs Python dependencies
- Runs unit tests
- Generates code coverage
- Publishes test results
- Packages the application
- Publishes a build artifact

## Technologies

- Python
- PyTest
- Git
- GitHub
- Azure DevOps
- Azure Pipelines
- YAML

## Project Structure

```text
python-azure-devops-cicd/
│
├── src/
│   └── calculator.py
│
├── tests/
│   └── test_calculator.py
│
├── requirements.txt
├── azure-pipelines.yml
├── .gitignore
└── README.md
