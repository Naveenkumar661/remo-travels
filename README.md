✈️ Remo Travels — Travel Planner Application
A full-stack travel platform where users can explore destinations, browse hotel listings, and manage bookings — built with React.js and Django REST Framework.
🔗 Live Demo: remo-travels.vercel.app

🚀 Features

🌍 Browse travel destinations with details and images
🏨 View hotel listings per destination
📅 Book and manage travel bookings
👤 User authentication (Register / Login)
📱 Fully responsive — mobile-first design
⚡ Fast and smooth UI with React + Vite


🛠️ Tech Stack
Frontend
TechnologyUsageReact.jsUI Components & RoutingTailwind CSSStyling & Responsive DesignViteBuild Tool & Dev Server
Backend
TechnologyUsagePython & DjangoServer & Business LogicDjango REST FrameworkREST API DevelopmentMySQLDatabase
Deployment
ServiceUsageVercelFrontend HostingRenderBackend HostingRailwayDatabase Hosting

📁 Project Structure
remo-travels/
├── src/                  # React frontend source
│   ├── components/       # Reusable UI components
│   ├── pages/            # Page components
│   └── main.jsx          # App entry point
├── travel_backend/       # Django backend
│   ├── api/              # REST API views & serializers
│   ├── models.py         # Database models
│   └── urls.py           # API routes
├── public/               # Static assets
└── vercel.json           # Vercel deployment config

⚙️ Getting Started
Prerequisites

Node.js >= 18
Python >= 3.10
MySQL

1. Clone the repository
bashgit clone https://github.com/Naveenkumar661/remo-travels.git
cd remo-travels
2. Setup Frontend
bashnpm install
npm run dev
3. Setup Backend
bashcd travel_backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
4. Environment Variables
Create a .env file in the backend folder:
envDEBUG=True
SECRET_KEY=your_secret_key
DATABASE_URL=your_mysql_connection_url
ALLOWED_HOSTS=localhost,127.0.0.1

🌐 API Endpoints
MethodEndpointDescriptionGET/api/destinations/List all destinationsGET/api/hotels/List hotels by destinationPOST/api/bookings/Create a bookingGET/api/bookings/List user bookingsPOST/api/auth/register/Register userPOST/api/auth/login/Login user

👨‍💻 Developer
Naveen Kumar E — Python Full-Stack Developer

📧 enaveen107003@gmail.com
🔗 LinkedIn
💻 GitHub


📄 License
This project is open source and available under the MIT License.
