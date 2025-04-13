# Go Web Application

This is a simple website written in Golang. It uses the `net/http` package to serve HTTP requests.

## Running the server

To run the server, execute the following command:

```bash
go run main.go
```

The server will start on port 8080. You can access it by navigating to `http://localhost:8080/courses` in your web browser.

## Looks like this

![Website](static/images/golang-website.png)


# go-web-app-devops This project is a continuously evolving DevOps learning initiative centered around a simple Go web application. The goal is to progressively explore and apply modern DevOps tools and best practices.

It starts with containerization using a multi-stage Dockerfile to build efficient, production-ready images. The app is then deployed on a local Kubernetes cluster using Minikube, with deployment managed through clean, modular Kubernetes manifests.

As the project grows, new tools and techniques will be integrated—focusing on improving CI/CD pipelines, monitoring, scaling, and more. It’s a hands-on journey to deepen practical DevOps skills step by step.
