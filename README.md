# Equipment Management API

FastAPI CRUD API para gestión de equipos industriales con persistencia relacional.

## Features

* CRUD completo (Create, Read, Update, Delete)
* Validación de datos con Pydantic
* Error handling (404)
* Persistencia de datos y migraciones de esquemas

## Tech Stack

* Python 3.10+
* FastAPI & Pydantic
* PostgreSQL
* SQLAlchemy & Alembic

## Installation

### 1. Clonar y configurar entorno
```bash
git clone <tu-url-del-repositorio>
cd equipment-management-api
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
