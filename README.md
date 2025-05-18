# Learning FastAPI 🚀

A sandbox repo where I follow tutorials, build mini-projects, and capture my notes while exploring **[FastAPI](https://fastapi.tiangolo.com/)**.

## Why FastAPI?

- **Speed to code**: automatic input validation (Pydantic) & instant interactive docs (Swagger UI / ReDoc).
- **Performance**: Starlette + Uvicorn under the hood (ASGI, async all the way).
- **Modern ecosystem**: SQLAlchemy, async ORMs, OAuth2/JWT, Celery/Redis, Docker/Kubernetes—works out of the box.

## Project layout

See the directory tree in this README for how things are organised.  Each tutorial or experiment lives in its own branch or sub-folder under `app/`.

| Branch / folder | Topic |
|-----------------|-------|
| `starter`       | “Hello, world” FastAPI + pytest |
| `crud-sqlalchemy` | Full CRUD with SQLModel + Alembic |
| …               | … |

## Getting started

```bash
git clone https://github.com/snikhil17/learning-fastapi.git
cd learning-fastapi
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
