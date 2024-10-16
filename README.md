# Flask App Kubernetes Deployment

This repository contains the files necessary to:

1. Run a simple Flask web app (`app.py`).
2. Containerize it with Docker (`Dockerfile`).
3. Deploy it to Kubernetes (`deployment.yaml` and `service.yaml`).

### Instructions

- To containerize the app, build the Docker image:
  ```bash
  docker build -t flask-app .
