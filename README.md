# Flask Python Application

##  Project Description

This is a simple **Python Flask web application**.
The application provides two web routes and can be deployed using *** local Flask server**.

##  Technologies Used

* Python
* Flask
* GitHub

##  Project Structure

```text
pythonapp-master/
│
├── app.py
└── README.md
```

##  Application Routes

### 1. Home Page

```text
/
```

URL:

```text
http://localhost:5000/
```

Response:

```text
successfully deployed python application through jenkins!!!!!!!!!, added webhook
```

### 2. HI Page

```text
/hi
```

URL:

```text
http://localhost:5000/hi
```

Response:

```text
Hiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiii from Flask & Docker
```

The routes and their responses are defined in the Flask application.

##  Installation

### Step 1: Install Python

Check Python:

```bash
python --version
```

or:

```bash
python3 --version
```

### Step 2: Install Flask

```bash
pip install flask
```

### Step 3: Run the Application

```bash
python app.py
```

The application runs on:

```text
http://localhost:5000
```

The application uses port `5000` by default and listens on `0.0.0.0`.

##  Open in Browser

Open:

```text
http://localhost:5000/
```

For the second page:

```text
http://localhost:5000/hi
```



RUN pip install flask

EXPOSE 5000

CMD ["python", "app.py"]
```

Build the Docker image:

```bash
docker build -t flask-app .
```

Run the container:

```bash
docker run -p 5000:5000 flask-app
```

Then open:

```text
http://localhost:5000
```


##  Requirements

Install:

```text
Python
Flask
Git
GitHub
```

##  Author

## pratibha Daware
![output application]()