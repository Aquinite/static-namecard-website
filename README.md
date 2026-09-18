# Namecard Website

A simple personal namecard site built with Flask, based on an HTML5 UP template. Deployed live on Render.

**Live site:** https://static-namecard-website.onrender.com

## What it is

A single-page online business card with my name, title, and social links. I used this project to learn how to actually deploy a simple Python web app, not just run it locally.

## Built with

- Flask 
- Gunicorn 
- HTML5 UP template 
- Render

## Running it locally

```
pip install -r requirements.txt
python server.py
```

## Running it like production (with Gunicorn)

```
pip install -r requirements.txt
gunicorn server:app
```

## Deployment notes

- Hosted as a Render Web Service 
- Free tier spins down when idle, so the first load after inactivity can take 10-20 seconds

## Future Features
- Changing the background to a different photo
- adding more buttons to future projects 
