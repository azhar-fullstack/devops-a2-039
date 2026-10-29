# devops-a2-039

Assignment 2 — Build, Containerize and Automate  
**DevOps for Cloud Computing (Lab)**

Student: **Azhar Mehmood**  
Roll number: **FA23-BAI-039**

## What this project is

A simple personal portfolio page (`index.html` + `style.css`) packaged with Docker (nginx) and automated with GitHub Actions. Every push to `main` checks the page and publishes a Docker image to Docker Hub.

## Links

- GitHub: https://github.com/azhar-fullstack/devops-a2-039
- Docker Hub: https://hub.docker.com/r/azharmehmood32/devops-a2

## Run locally with Docker

```bash
docker build -t azharmehmood32/devops-a2:manual .
docker run -d -p 8080:80 --name page azharmehmood32/devops-a2:manual
```

Open http://localhost:8080

## Extra section

Roll number ends with **9** → **Contact** section (email + GitHub profile).
