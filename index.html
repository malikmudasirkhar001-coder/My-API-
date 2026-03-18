from fastapi import FastAPI
import uvicorn
import os

app = FastAPI()

# Khalis Data Store (Aapke 5 Records)
db = [
    {
        "id": 1,
        "name": "Samina Bibi",
        "phone": "03290221378",
        "network": "Jazz",
        "address": "Cah hayat khar wala gurmani garbi"
    },
    {
        "id": 2,
        "name": "Aziz Bibi",
        "phone": "03084191378",
        "network": "Jazz",
        "address": "Cha hayat wala"
    },
    {
        "id": 3,
        "name": "Mudasir Abbas khar",
        "phone": "03291667662",
        "network": "Jazz",
        "address": "Cah hayat khar wala gurmani garbi"
    },
    {
        "id": 4,
        "name": "Muhammad Iqbal",
        "phone": "03007485366",
        "network": "Jazz",
        "address": "Cah hayat Khar gurmani garbi"
    },
    {
        "id": 5,
        "name": "Basheer Ahmad",
        "phone": "03046754893",
        "network": "Jazz",
        "address": "Caha hayat wala khar gurmani garbi"
    }
]

@app.get("/")
def home():
    return {"message": "API Active", "records_count": len(db)}

@app.get("/all")
def get_all():
    return db

@app.get("/search")
def find(q: str):
    return [i for i in db if q.lower() in i["name"].lower() or q in i["phone"]]

if __name__ == "__main__":
    port = int(os.environ.get("PORT", 8000))
    uvicorn.run(app, host="0.0.0.0", port=port)
