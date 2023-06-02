# FastAPI/Python: Starter API Code Sample

This Python code sample demonstrates how to build an API server using FastAPI that is secure by design.

Visit the ["FastAPI/Python Code Samples: API Security in Action"](https://developer.auth0.com/resources/code-samples/api/fastapi) section of the ["Auth0 Developer Resources"](https://developer.auth0.com/resources) to explore how you can secure FastAPI applications written in Python by implementing endpoint protection and authorization with Auth0.

## Why Use Auth0?

Auth0 is a flexible drop-in solution to add authentication and authorization services to your applications. Your team and organization can avoid the cost, time, and risk that come with building your own solution to authenticate and authorize users. We offer tons of guidance and SDKs for you to get started and [integrate Auth0 into your stack easily](https://developer.auth0.com/resources/code-samples/full-stack).

## Set Up and Run the FastAPI Project

## Run the Project

### Requirements

Python 3.10
pip 22.2.2

## Set up the Development Environment

Create a virtual environment under the root project directory:

**macOS/Linux:**

```bash
python3 -m venv venv
```

**Windows:**

```bash
py -3 -m venv venv
```

Then, activate the virtual environment:

**macOS/Linux:**

```bash
. venv/bin/activate
```

**Windows:**

```bash
venv\Scripts\activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Set up the environment variables

Create a `.env` file under the root project directory:

```bash
touch .env
```

Next, populate it with the following environment variables:

```bash
PORT=6060
CLIENT_ORIGIN_URL=http://localhost:4040
RELOAD=True
```

### Run the api server

```bash
python3 application/main.py
```
