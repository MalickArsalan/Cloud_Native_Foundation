# Endpoints for Application Status

This exercise aims to extend a Python Flask web application with status and metrics endpoints.

**Environment Setup
Set up your environment to extend a Python Flask application:**

- [X] Clone the [course exercise repository](https://github.com/udacity/nd064_course_1) using git
- [X] Navigate inside the `exercises/python-helloworld` folder
- [X] Using `python` or `flask run` commands, run the `app.py` application
- [X] Access Hello World application on your local browser (note: Python Flask uses port `5000` by default)
- [X] Open your editor of choice (IDE or vim) to edit the Hello World application

Once all the pre-requisites are completed, you can get started on developing endpoints to describe the application state.

**Exercise**
Extend the Python Flask application with /status and /metrics endpoints, considering the following requirements:

Both endpoints should return an HTTP 200 status code
Both endpoints should return a JSON response e.g. `{"user": "admin"}`. (Note: the JSON response can be hardcoded at this stage)
The `/status` endpoint should return a response similar to this example: `result: OK - healthy`
The `/metrics` endpoint should return a response similar to this example: `data: {UserCount: 140, UserCountActive: 23}`
