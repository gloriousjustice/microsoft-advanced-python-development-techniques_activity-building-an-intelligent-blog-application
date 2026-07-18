# Intelligent Blog Application

This project is a dynamic, full-stack web application developed as an advanced practical project within the **Advanced Python Development Techniques** curriculum, a component of the **Microsoft Python Development Professional Certificate** program on Coursera. It was engineered to practice test-driven development (TDD) pipelines, advanced debugging workflows, and automated backend route validation.

---

## Technical Specifications and Scope

### Academic and Professional Credential Context
* Certification Program: Microsoft Python Development Professional Certificate
* Platform Provider: Coursera
* Course Focus: Advanced Python Development Techniques, Test-Driven Development (TDD), and Code Verification

### Backend Architecture
* Framework: Flask (Python 3)
* Testing Suite: Pytest framework with automated execution via python3 -m pytest
* Testing Methods: Test-Driven Development (TDD) loop, including endpoint state testing, method isolation, and integration mock fixtures
* Concurrency & Storage: Local in-memory dictionary and list structures optimized for rapid storage operations

### Frontend Architecture
* Technologies: HTML5, CSS3, JavaScript (ES6 Vanilla API)
* Interface Engine: Jinja2 Template rendering
* Client Scripting: Asynchronous DOM manipulation via fetch API operations to manage data transfers seamlessly without page reloads

---

## Project Performance and Quantifiable Data Points

When preparing resume bullets or project portfolio summaries, use the following audited structural metrics from this codebase:

### 1. Test Coverage and Quality Assurance
* Total Tests Handled: 5 independent integration test cases mapping route security, parameter validation, and initialization states.
* Test Status: Successfully resolved codebase discrepancies to achieve a 100% test pass rate across the integration suite.
* Code Framework: Managed the separation of test configurations by implementing clean setup code within tests/conftest.py.

### 2. Interface Endpoints and Routes Created
* Data Retrieval: Implemented the primary GET route to cleanly format and fetch raw data arrays for user display.
* Data Intake: Engineered a robust POST route to securely parse incoming JSON payload variables.
* Data Validation: Programmed server-side error validation logic to intercept empty or malformed strings, returning standardized HTTP status codes.

---

## Project Execution Guide

### 1. Local Environment Deployment
Install the required packages to establish the project runtime environment:
```bash
pip install Flask pytest
```

### 2. Testing Execution
Execute the automated test suite to ensure backend route logic complies with project guidelines:
```bash
python3 -m pytest
```

### 3. Server Startup
Launch the development framework server:
```bash
python3 app.py
```
Access the interface by opening your browser to: http://127.0.0
