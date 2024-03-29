![](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)
![](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
***

# Introduction

This project is a Flask application that allows users to drag and drop Excel files into input elements on a single webpage, where the files will be processed and returned as new formatted files. The application supports multiple input elements, each performing different formatting tasks.

## Getting Started

To get started with this project, you will need to have Poetry installed on your machine. You can install the dependencies by running the following command:
```
poetry install
```

Before running the app, you will need to configure the application by setting the following environment variables in server/.flaskenv:

    FLASK_APP=app
    FLASK_ENV=development
    FLASK_DEBUG=1

Once the dependencies are installed, you can run the application by first navigating to server followed by running the following command:
```
poetry run flask run
```

## Usage

To use the application, simply navigate to the root URL (http://localhost:5000/) in your web browser. Once the page loads, you can drag and drop Excel files into the designated input elements. Each input element is labeled with its corresponding formatting task. Once the file is processed, you will be prompted to download the new formatted file.


## References

- Flask (http://flask.pocoo.org/)
- Poetry (https://python-poetry.org/)
- openpyxl (https://openpyxl.readthedocs.io/)


:octocat:

<!-- https://dvj70ijwahy8c.cloudfront.net/Registrator/icon | # -->
