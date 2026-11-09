# Currency Exchange API - C# .NET & PostgreSQL (Talento Tech ANI)

> [!NOTE]
> **Archived Academic Project**  
> This repository is a read-only historical archive of coursework developed for academic evaluation.

## Overview
RESTful backend API for exchange rate calculations and currency management, built for the **Talento Tech - Arquitectura en Nube Innovadora** program. Implemented in C# .NET with PostgreSQL persistence, following domain-driven hexagonal separation of concerns.

## Solution Structure
* **`apiCambiosMoneda.Core`**: Central contracts and shared abstractions.
* **`apiCambiosMoneda.Dominio`**: Business entities, validation rules, and exchange rate logic.
* **`apiCambiosMoneda.Aplicacion`**: Service interfaces and request handlers.
* **`apiCambiosMoneda.Infraestructura.Repositorio`**: Entity Framework Core data context and PostgreSQL repository implementations.
* **`apiCambiosMoneda.Presentacion`**: Web API endpoints, routing, and HTTP middleware.
* **`apiCambiosMoneda.Test`**: Automated unit test suite.

## Deployment
* Docker multi-stage build support (`Dockerfile`).
* Automated Jenkins CI/CD pipeline (`Jenkinsfile`).

