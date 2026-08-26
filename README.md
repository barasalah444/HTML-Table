
# HTML Table Assignment

A Flask web application that dynamically renders user data into a styled Bootstrap HTML table using Jinja2 templates.

## Overview

This project demonstrates how to pass dynamic data (a list of dictionaries) from a Flask backend to an HTML frontend and display it cleanly using Bootstrap 5 styling.

## Key Features

* Flask routing and template rendering.
* Jinja2 `for` loop iteration to generate table rows dynamically.
* Concatenation of first and last names into a combined full name column.
* Integrated Bootstrap 5 styling via CDN for a responsive design.

## Project Structure

```text
├── server.py
└── templates/
    └── index.html
