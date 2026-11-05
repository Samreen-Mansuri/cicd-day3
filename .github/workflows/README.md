# CI/CD Day 3 — Containerized & Published

![CI](https://github.com/Samreen-Mansuri/cicd-day3/actions/workflows/ci.yml/badge.svg)

Day 3 of my 7-day CI/CD series. The pipeline now packages the app into a Docker container and publishes it to GitHub Container Registry:
- A **Flask** app with a small API
- A **Dockerfile** building a slim, production-style image
- A pipeline that runs tests, then (only if they pass) builds and pushes the image to ghcr.io

**Tech:** Python · Flask · Docker · GitHub Actions · GHCR