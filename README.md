# 🔥 FireApp

_A comprehensive monitoring system for tracking fire incidents across cities and countries worldwide._

![FireApp Screenshot](https://via.placeholder.com/800x400?text=FireApp+Screenshot) <!-- Replace with actual screenshot -->

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Git
- pip

### 📥 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/FireApp.git
   cd FireApp

### Set Up Virtual Environment (Recommended)

python -m venv .env
source .env/bin/activate  # Linux/Mac
.\.env\Scripts\activate  # Windows

### Install Dependencies

pip install -r requirements.txt

### 🛠️ Configuration

Create a .env file in the root directory:

SECRET_KEY=your_secret_key_here
DEBUG=True
DATABASE_URL=sqlite:///db.sqlite3

### Apply database migrations:

python manage.py migrate

### ▶️ Running the Application
Start the development server:

python manage.py runserver

Visit http://localhost:8000 in your browser.

### 🌍 Project Structure

FireApp/
├── app/                  # Main application code
│   ├── models.py         # Database models
│   ├── views.py          # Application logic
│   └── templates/        # HTML templates
├── fireapp/              # Project configuration
│   ├── settings.py       # Django settings
│   └── urls.py           # URL routing
├── .env                  # Environment variables
├── requirements.txt      # Dependencies
└── manage.py             # Django management script

### 🤝 Authors

Jean Carlo D. Yap
Ronel Vincent C. Loquillano