# Gutenberg Text Cleaner

A Flask web service that fetches, cleans, and analyzes text from Project Gutenberg URLs.

---

## 📋 Project Overview

This web application demonstrates basic Natural Language Processing (NLP) techniques by:
- Fetching text files from Project Gutenberg URLs
- Removing Gutenberg-specific headers, footers, and metadata
- Normalizing and tokenizing text
- Calculating comprehensive text statistics (character count, word count, sentence count, averages)
- Generating extractive summaries
- Displaying results through a clean, modern web interface

The project serves as a practical introduction to text preprocessing, web development with Flask, and RESTful API design.

---

## 📁 Project Structure

```
scaffolding-assignment-3/
├── app.py                      # Flask web application with API endpoints
├── starter_preprocess.py       # Text preprocessing class with all methods
├── templates/
│   └── index.html             # Web interface with modern gradient design
├── requirements.txt            # Python dependencies (Flask, requests)
├── test_setup.py              # Environment verification script
├── README.md                  # This file
└── screenshots/               # Screenshots of working application
    ├── homepage.png
    ├── results.png
    └── statistics.png
```

### Key Files

- **`app.py`**: Main Flask application with REST API endpoints (`/api/clean`, `/api/analyze`)
- **`starter_preprocess.py`**: TextPreprocessor class containing text cleaning and analysis methods
- **`templates/index.html`**: Frontend web interface for user interaction
- **`requirements.txt`**: Python package dependencies

---

## 🚀 Setup and Installation

### Prerequisites

- Python 3.9 or higher
- pip (Python package manager)
- Git (for cloning the repository)

### Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/leetkavaiya/scaffolding3_startup.git
   cd scaffolding3_startup
   ```

2. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Verify installation (optional):**
   ```bash
   python test_setup.py
   ```

---

## ▶️ Running the Application

1. **Start the Flask server:**
   ```bash
   python app.py
   ```

2. **Open your web browser and navigate to:**
   ```
   http://localhost:5000
   ```

3. **Using the application:**
   - Enter a Project Gutenberg `.txt` URL in the input field
   - Click "Clean & Analyze Text" button
   - View the results including statistics, summary, and text preview

### Example URLs to Test

- Pride and Prejudice: `https://www.gutenberg.org/files/1342/1342-0.txt`
- Frankenstein: `https://www.gutenberg.org/files/84/84-0.txt`
- Alice in Wonderland: `https://www.gutenberg.org/files/11/11-0.txt`
- Moby Dick: `https://www.gutenberg.org/files/2701/2701-0.txt`

---

## 📚 Dependencies

- **Flask 2.3.0** - Web framework
- **requests 2.31.0** - HTTP library for fetching URLs
- **Werkzeug 2.3.0** - WSGI utility library

Install all dependencies with:
```bash
pip install -r requirements.txt
```

---

## 🙏 Acknowledgments

- **Original Repository:** [delveccj/scaffolding3_startup](https://github.com/delveccj/scaffolding3_startup) by Professor Justin Del Vecchio
- **Course:** Basics of AI - Fall 2025, University at Buffalo
- **Project Gutenberg:** For providing free access to thousands of classic literary works
- **Flask Framework:** For making web development in Python straightforward and elegant

---

## 📄 License

This project is created for educational purposes as part of the Basics of AI course at University at Buffalo.

---

**Course:** Basics of AI - Fall 2025  
**Institution:** University at Buffalo