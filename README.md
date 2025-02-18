# Urdu-Heritage-Translation-Project
This project aims to digitize and translate historical Urdu documents, making them accessible for modern understanding. It uses OCR (Optical Character Recognition) and NLP (Natural Language Processing) to extract, recognize, and translate old Urdu scripts.

# Features
✅ OCR system for recognizing historical Urdu text
✅ Translation into modern Urdu and English
✅ User-friendly interface for browsing translated documents
✅ Database for storing and retrieving translated works
Technologies Used
Python (OCR & NLP processing)
Flask (Backend API)
React.js (Frontend UI)
PostgreSQL (Database)
TensorFlow/Keras (OCR & translation models)
How to Use
Upload an old Urdu document.
The OCR system extracts the text.
The NLP module translates it into modern Urdu/English.
View and download the translated document.
Installation
To run the project locally:
# Clone this repository
git clone https://github.com/your-username/urdu-heritage-translation.git

# Navigate to the project folder
cd urdu-heritage-translation

# Install dependencies
pip install -r requirements.txt

# Start the backend server
python app.py

# Run the frontend
npm start

# Open the app in the browser
http://localhost:3000/
File Structure

├── backend/           Flask backend
│   ├── app.py         Main server file
│   ├── ocr.py         OCR processing
│   ├── translation.py   NLP translation
├── frontend/          React.js frontend
│   ├── src/
│   │   ├── App.js     Main application component
│   │   ├── styles.css   Styling for UI
├── database/         PostgreSQL scripts
├── models/           OCR & NLP models
├── public/           Static assets
└── README.md         Project documentation
Live Demo


License
This project is free to use for educational and research purposes.

Preserving and modernizing Urdu heritage for future generations! 📜✨
