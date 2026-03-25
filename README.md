Remo Travels - Full Stack Travel Planner
Remo Travels is a comprehensive full-stack web application designed to help users discover destinations, book hotels, and manage their travel itineraries seamlessly. Built with a modern tech stack, it focuses on performance, responsive design, and a smooth user experience.

🚀 Live Demo
View Live Project (Replace with your actual Vercel link)

🛠️ Tech Stack
Frontend
React.js – UI components and state management.

Vite – Lightning-fast build tool and development server.

Tailwind CSS – Modern, utility-first styling for responsive design.

Lucide React – For clean, scalable iconography.

Backend
Python (Django/DRF) – Robust REST API architecture.

MySQL – Reliable relational database management.

CORS Headers – Configured for secure cross-origin communication.

✨ Features
User Authentication: Secure login and signup modals for personalized travel planning.

Destination Discovery: Browse popular travel spots with detailed descriptions.

Hotel Booking System: Search and book accommodations directly within the app.

Dynamic UI: Fully responsive layout optimized for mobile, tablet, and desktop.

Production Ready: Configured for deployment on platforms like Vercel with optimized API URLs.

📁 Project Structure
Plaintext
├── public/              # Static assets
├── src/                 # React frontend source code
│   ├── components/      # Reusable UI components
│   ├── api/             # API configuration (Production/Local)
│   └── ...
├── travel_backend/      # Django backend application
│   ├── settings.py      # Production & CORS configuration
│   └── ...
├── vercel.json          # Deployment configuration
└── package.json         # Frontend dependencies
⚙️ Installation & Setup
1. Clone the repository
Bash
git clone https://github.com/Naveenkumar661/remo-travels.git
cd remo-travels
2. Frontend Setup
Bash
# Install dependencies
npm install

# Start development server
npm run dev
3. Backend Setup
Bash
cd travel_backend
# Set up a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations and start server
python manage.py migrate
python manage.py runserver
📝 License
This project is open source. Feel free to use it for your own learning or portfolio.
