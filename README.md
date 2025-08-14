Calorie Analyzer

Calorie Analyzer is a Python-based web application developed using Django that estimates the calorie content of food items. The application provides a simple and interactive interface for users to input food details and receive nutritional information instantly.

📝 Features

User-Friendly Interface
Enter food items through a clean web interface for quick calorie estimation.

Nutritional Analysis
Calculates approximate calorie values based on user inputs.

Backend Support
Handles data processing efficiently using Django.

Database Integration
Uses SQLite to store user inputs and analysis results.

💻 Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: Python, Django

Database: SQLite

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/Renukanarayan/Calorie_Analyzer.git


Navigate to the project directory

cd Calorie_Analyzer


Install dependencies

pip install -r requirements.txt


Apply database migrations

python manage.py migrate


Run the development server

python manage.py runserver


Access the application
Open your browser and go to http://127.0.0.1:8000/.

📂 Project Structure
Calorie_Analyzer/
│
├── calorie_analyzer/      # Django project folder
├── db.sqlite3             # SQLite database
├── manage.py              # Django management script
├── templates/             # HTML templates
├── static/                # CSS and JS files
└── requirements.txt       # Python dependencies

🚀 Usage

Launch the application.

Enter the food item in the input field.

Submit to get the estimated calorie content.

View results instantly on the same page.

🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

📜 License

This project is open-source and available under the MIT License.
