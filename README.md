# Recipe REST API (built with Django)

## Tech Stack

- Python 3.7
  - PEP-8 Guidelines
- Django 2 (web framework, ORM, admin)
- Django REST Framework (authentication, ViewSets, Serializers, Browsable API)
- PostgreSQL (enterprise database)
- Docker (lightweight virtual machine)
- Travis-CI (automate testing and linting)
  - linting with flake8
- TDD Methodologies

## API

### Manage Users

- /api/user/create
- /api/user/token
- /api/user/me

### Manage Recipes

- /api/recipe/tags
- /api/recipe/ingredients
- /api/recipe/recipe
- /api/recipe/recipe/<id>
- /api/recipe/recipe/<id>/upload-image
