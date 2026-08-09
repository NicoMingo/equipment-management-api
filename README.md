# Equipment Management API

FastAPI CRUD API para gestión de equipos industriales con persistencia relacional.

---

## ✨ Features

- ✅ CRUD completo (Create, Read, Update, Delete)
- ✅ Validación de datos con Pydantic
- ✅ Error handling (404)
- ✅ Persistencia de datos y migraciones de esquemas

---

## 🛠️ Tech Stack

| Tecnología | Uso |
|---|---|
| Python 3.10+ | Lenguaje base |
| FastAPI & Pydantic | Framework y validación |
| PostgreSQL | Base de datos relacional |
| SQLAlchemy & Alembic | ORM y migraciones |

---

## 🚀 Installation

**1. Clonar y configurar entorno**
```bash
git clone <tu-url-del-repositorio>
cd equipment-management-api
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

**2. Instalar dependencias**
```bash
pip install -r requirements.txt
```

**3. Variables de entorno**

Crear un archivo `.env` en la raíz del proyecto:
```env
DATABASE_URL=postgresql://usuario:contraseña@localhost/nombre_db
```

**4. Configurar base de datos**
```bash
alembic upgrade head
```

---

## ▶️ Usage

```bash
uvicorn main:app --reload
```

API disponible en **`http://127.0.0.1:8000`**
Documentación interactiva en **`/docs`**
