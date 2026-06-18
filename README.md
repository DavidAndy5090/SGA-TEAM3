# Sistema de Gestión Académica (SGA)
## Sprint 0 Goal
El equipo tiene el entorno configurado, el repositorio Git Flow activo,
los wireframes de las pantallas principales y el Repositorio + Git Flow +
Commits.
## Equipo — [Nombre del Equipo]
| Rol | Integrante | GitHub |
|---------------|---------------------|------------------|
| Product Owner | [Nombre] | @usuario |
| Scrum Master | [Nombre] | @usuario |
| Backend Dev | [Nombre] | @usuario |
| Frontend Dev | [Nombre] | @usuario |
| QA / DevOps | [Nombre] | @usuario |
## Stack Tecnológico
- Python 3.12+ | Django 5.x | DRF 3.15+
- Bootstrap 5 | SQLite (dev) | PostgreSQL (prod)
## Cómo ejecutar el proyecto localmente
```bash
git clone https://github.com/[usuario]/sga-[nombre-equipo].git
cd sga-[nombre-equipo]
python -m venv venv
venv\Scripts\activate # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
Navegar a http://127.0.0.1:8000/