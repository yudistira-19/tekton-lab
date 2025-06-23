# 🐍 Tekton Flask CI/CD Pipeline

## 🎯 Goal
Build & deploy a Flask app on OpenShift using Tekton Pipelines

## 📦 Features
- Build Docker image using Tekton Task (Buildah)
- Push to OpenShift internal registry
- Deploy with `oc new-app`

## 📂 Structure
- app.py → Flask app
- Dockerfile → Image build
- tekton/ → CI/CD YAMLs


## 🛠️ Stack
- OpenShift 4.x
- Tekton Pipelines
- Flask + Docker
- OpenShift Registry

## 🧠 Author
Created by 
