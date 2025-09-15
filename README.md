📝 Productivity Pro - Todo Application

https://github.com/Aqibkhan037/Todo_Django_Application/blob/main/screenshot.jpg
A beautiful, feature-rich todo application built with React frontend and Django REST Framework backend. Designed to help you stay organized and productive with an intuitive interface and powerful features.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

✨ Features
🎯 Core Functionality
✅ Create, read, update, and delete tasks

✅ Mark tasks as complete/incomplete

✅ Clean, modern user interface

✅ Responsive design (works on desktop, tablet, and mobile)
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

🚀 Advanced Features
🔍 Smart Search - Find tasks quickly

🏷️ Categories - Organize tasks by category

⚡ Priority Levels - Highlight important tasks (High/Medium/Low)

📅 Due Dates - Never miss a deadline

🎯 Task Filtering - View all, active, or completed tasks

📊 Statistics Dashboard - Track your productivity

🗑️ Bulk Operations - Clear completed tasks with one click

🎨 User Experience
✨ Beautiful UI - Modern design with smooth animations

🎨 Visual Indicators - Color-coded priorities and categories

⚡ Real-time Updates - Instant feedback on all actions

📱 Mobile-Friendly - Responsive design for all devices

🎯 Keyboard Shortcuts - Press Enter to add tasks

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

🛠️ Technology Stack
Frontend
React 18.2.0 - Modern UI framework

Axios - HTTP client for API requests

CSS3 - Custom styling with Flexbox and Grid

React Hooks - Modern state management

Backend
Django 4.2 - Powerful Python web framework

Django REST Framework 3.14 - Building REST APIs

SQLite/PostgreSQL - Database management

CORS Headers - Cross-origin resource sharing
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

📦 Installation & Setup
Prerequisites
Node.js 14+ and npm

Python 3.8+

pip (Python package manager)

Git

Frontend Setup (React)
Clone the repository

bash
git clone https://github.com/your-username/productivity-pro.git
cd productivity-pro/frontend
Install dependencies

bash
npm install
Configure environment variables

bash
# Create .env file in frontend directory
REACT_APP_API_BASE_URL=http://localhost:8000/api
Start the development server

bash
npm start
The app will open at http://localhost:3000

Backend Setup (Django)
Navigate to backend directory

bash
cd ../backend
Create virtual environment

bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Python dependencies

bash
pip install -r requirements.txt
Run database migrations

bash
python manage.py migrate
Create superuser (optional)

bash
python manage.py createsuperuser
Start the development server

bash
python manage.py runserver
The API will be available at http://localhost:8000/api

🚀 Deployment
Frontend Deployment (Netlify/Vercel)
bash
# Build the project
npm run build

# Deploy to your preferred platform
# The build folder contains optimized production files
Backend Deployment (Heroku/Railway/DigitalOcean)
bash
# Ensure requirements.txt is updated
pip freeze > requirements.txt

# Add Procfile for Heroku
echo "web: gunicorn your_project_name.wsgi --log-file -" > Procfile

# Deploy to your preferred platform
📖 API Documentation
Endpoints
Method	Endpoint	Description
GET	/api/todos/	Retrieve all tasks
POST	/api/todos/	Create a new task
GET	/api/todos/{id}/	Retrieve a specific task
PATCH	/api/todos/{id}/	Update a task
DELETE	/api/todos/{id}/	Delete a task
GET	/api/categories/	Retrieve all categories
Example Request
javascript
// Create a new task
const response = await axios.post('/api/todos/', {
  title: 'Learn React Hooks',
  completed: false,
  category: 1,
  priority: 'high',
  due_date: '2023-12-31'
});
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

🎯 Usage Guide
Adding Tasks: Type in the input field and press Enter or click "Add Task"

Completing Tasks: Click the checkbox next to any task

Editing Tasks: Click the "Edit" button, make changes, and save

Filtering: Use the filter buttons to view All, Active, or Completed tasks

Searching: Type in the search box to find specific tasks

Setting Priorities: Use the priority dropdown when adding/editing tasks

Adding Categories: Assign categories to keep tasks organized

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

🐛 Troubleshooting
Common Issues
CORS Errors: Ensure Django CORS headers are properly configured

Connection Refused: Check if both frontend and backend servers are running

API 404 Errors: Verify your API endpoint URLs in the frontend

Solutions
bash
# If you encounter package issues
npm install --force

# If Django migrations fail
python manage.py makemigrations
python manage.py migrate

# If port 3000 is busy
npm start -- --port 3001
🤝 Contributing
We welcome contributions! Please feel free to submit pull requests or open issues for bugs and feature requests.

Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

📝 Learning Journey
This project was an incredible learning experience that taught me:

React Hooks (useState, useEffect, custom hooks)

API Integration with Axios and error handling

Modern CSS techniques including Flexbox and Grid

State Management patterns in React

Django REST Framework serializers and viewsets

CORS Configuration for cross-origin requests

Git Workflow and version control best practices

Debugging Techniques for full-stack applications

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

🙏 Acknowledgments
React team for the amazing framework

Django REST Framework for the robust API tools

Open source community for countless learning resources

All contributors who helped improve this project

📄 License
This project is licensed under the MIT License - see the LICENSE.md file for details.
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

📞 Support
If you have any questions or need help, please:

Email me at aqibkhan1582000@gmail.com

