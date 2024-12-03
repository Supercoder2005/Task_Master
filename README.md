
# Task Master

Task Master is a simple, elegant, and user-friendly task management web application. It allows users to create, update, and delete tasks with ease, helping them stay organized and productive.

## Features

- Create new tasks
- View all tasks in a beautifully designed table
- Update existing tasks
- Delete tasks
- Responsive design for both desktop and mobile devices

## Technologies Used

- Python
- Flask (Web Framework)
- SQLite (Database)
- HTML5
- CSS3
- Jinja2 (Templating Engine)

## Setup and Installation

1. Clone the repository:


## How To Run
1. Install `virtualenv`:
```
$ pip install virtualenv
```

2. Open a terminal in the project root directory and run:
```
$ virtualenv env
```

3. Then run the command:
```
$ .\env\Scripts\activate
```

4. Then install the dependencies:
```
$ (env) pip install -r requirements.txt
```

5. Finally start the web server:
```
$ (env) python app.py
```

This server will start on port 5000 by default. You can change this in `app.py` by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
```
