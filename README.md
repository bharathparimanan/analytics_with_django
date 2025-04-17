# Data Analysis Web API with Django REST Framework

[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![Django Version](https://img.shields.io/badge/django-4.x-green.svg)](https://www.djangoproject.com/)
[![DRF Version](https://img.shields.io/badge/djangorestframework-3.x-yellow.svg)](https://www.django-rest-framework.org/)
[![Libraries](https://img.shields.io/badge/libraries-pandas%20%7C%20numpy%20%7C%20matplotlib%20%7C%20seaborn-brightgreen.svg)](https://pandas.pydata.org/ | https://numpy.org/ | https://matplotlib.org/ | https://seaborn.pydata.org/)
[![License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](LICENSE) ## Overview

This project is a web application built using the Django framework and Django REST Framework (DRF) to provide a powerful API for data analysis. It allows users to upload data files (currently supporting CSV and Parquet formats), process them using the Python data science libraries Pandas and NumPy, generate insightful analytics, and optionally load the processed data or analysis results into a database.

This API is designed to be easily integrated with front-end applications or other systems that require data analysis capabilities.

## Features

* **File Upload:** Secure API endpoints for uploading data files in CSV and Parquet formats.
* **Data Parsing:** Robust parsing of uploaded files using Pandas to handle various data structures.
* **Data Processing:** Utilizes Pandas and NumPy for efficient data cleaning, transformation, and analysis.
* **Analytics Generation:** Generates meaningful analytics based on the processed data (e.g., descriptive statistics, correlations, etc.).
* **Data Visualization (Optional via API):** Can be configured to generate basic visualizations using Matplotlib and Seaborn, potentially serving image files or data for front-end rendering.
* **Database Integration:** Supports loading processed data or analysis results into a Django-configured database for persistence and future retrieval.
* **RESTful API:** Provides a clear and standardized API using Django REST Framework for easy interaction.

## Technologies Used

* **Python:** Programming language for the entire project.
* **Django:** High-level Python web framework.
* **Django REST Framework:** Toolkit for building Web APIs with Django.
* **Pandas:** Library for data manipulation and analysis.
* **NumPy:** Library for numerical computing.
* **Matplotlib:** Library for creating static, interactive, and animated visualizations.
* **Seaborn:** Library for statistical data visualization (built on Matplotlib).
* **Database:** (Specify your database here, e.g., PostgreSQL, SQLite, MySQL)

## Getting Started

### Prerequisites

* **Python 3.x** installed on your system.
* **pip** package installer for Python.