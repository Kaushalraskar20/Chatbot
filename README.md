📘 Smart PDF / PPT Chatbot (Offline, No LangChain)

A lightweight offline AI chatbot that reads PDF or PPT documents, creates semantic embeddings, and answers questions using similarity search — without LangChain or internet.

Perfect for students, researchers, and developers who want private document Q&A.

🚀 Features

✔ Works completely offline
✔ Supports PDF and PPTX files
✔ Uses Sentence Transformers embeddings
✔ Smart chunking + similarity search
✔ Non-repetitive answers
✔ Adjustable confidence threshold
✔ Clean summarized answers
✔ Lightweight & fast

🧠 How It Works

Extract text from PDF/PPT

Split text into chunks

Generate embeddings using all-MiniLM-L6-v2

Store embeddings in JSON

Compare question embedding with chunks

Return most relevant summarized answer

🛠️ Tech Stack

Python

PyPDF2

python-pptx

Sentence Transformers

NumPy

JSON
