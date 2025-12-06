# main.py
from fastapi import FastAPI

app = FastAPI()

# 1. Root Endpoint
@app.get("/")
def read_root():
    return {"message": "Hello from Render Ch!", "status": "active"}

# 2. Item Endpoint (Demonstrates path parameters)
@app.get("/items/{item_id}")
def read_item(item_id: int):
    return {"item_id": item_id, "name": f"Item Number {item_id}"}
