# SauceDemo Automation Framework

![Tests](https://github.com/Quarahilde/saucedemo-automation-framework/actions/workflows/tests.yml/badge.svg)

Automated testing framework for SauceDemo e-commerce application using Python, Playwright, and pytest.

## Features
- Page Object Model design pattern
- 51 comprehensive tests
- Automated CI/CD pipeline
- HTML test reports

## Technologies
- Python 3.14
- Playwright 1.57.0
- pytest 9.0.2
- GitHub Actions

## Project Structure
```
├── .github/workflows/    # CI/CD configuration
├── pages/                # Page Object classes
├── tests/                # Test files
└── conftest.py           # pytest fixtures
```

## Setup

### Prerequisites
- Python 3.12+
- pip

### Installation
```bash
# Clone the repository
git clone https://github.com/Quarahilde/saucedemo-automation-framework.git
cd saucedemo-automation-framework

# Install dependencies
pip install -r requirements.txt

# Install Playwright browsers
playwright install chromium
```

## Running Tests
```bash
# Run all tests
pytest tests/

# Run with HTML report
pytest tests/ --html=report.html --self-contained-html

# Run specific test file
pytest tests/test_login.py
```

## CI/CD

Tests run automatically on every push via GitHub Actions.

View test results: [Actions Tab](https://github.com/Quarahilde/saucedemo-automation-framework/actions)

## Test Coverage

- **Login Tests:** 9 tests
- **Product Tests:** 18 tests
- **Cart Tests:** 16 tests
- **Checkout Tests:** 8 tests

**Total:** 51 tests

## Author

Mariusz Danielak