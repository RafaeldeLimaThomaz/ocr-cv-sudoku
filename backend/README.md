````md
# Backend (FastAPI)

## Structure

- `app/api.py`: routes and endpoints
- `app/pipeline.py`: orchestrates preprocessing → recognition → solving
- `app/recognizer.py`: CNN-based digit recognizer
- `training/`: scripts for model training

## Run locally

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```
````
