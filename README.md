# CI/CD Tools and Practices Final Project

Project name: `ci-cd-final-project`

This repository contains the final project for the CI/CD Tools and Practices course.

## CI/CD

- GitHub Actions checks the service with flake8 and runs the unit tests with nose.
- OpenShift Pipelines cleans the workspace, clones this repository, lints and tests the service, builds a container image, and deploys it to the lab cluster.
