PROJECT : Simple Book API
Building a RESTful API to manage a list of books by using CRUD operations through Flask and Python.

Structure :
book_api/
├── book.py
├── requirements.txt
└── README.md

To Setup :
1. Install dependencies:
   pip install -r requirements.txt

2. Run the server:
   python Book.py

3. Access API endpoints at `http://127.0.0.1:5000/`
   ## 📖 Endpoints
   - `GET /books` → Get all books
   - `GET /books/<id>` → Get a single book
   - `POST /books` → Add a new book (JSON: { "title": "", "author": "" })
   - `PUT /books/<id>` → Update a book
   - `DELETE /books/<id>` → Delete a book

