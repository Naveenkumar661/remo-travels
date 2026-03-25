🌍 Remo Travels - Full Stack Travel Planner
Remo Travels is a comprehensive full-stack web application designed to streamline travel planning. It allows users to browse destinations, check hotel availability, and manage bookings through a seamless, responsive interface.

🛠️ Tech Stack
Frontend
React.js: Functional components and Hooks for state management.

Tailwind CSS: Modern, utility-first styling for a responsive UI.

Vite: Fast build tool and development server.

Axios: For handling asynchronous API calls to the backend.

Backend
Python & Django: Robust REST framework for business logic and API endpoints.

MySQL: Relational database for storing user data, hotel listings, and booking records.

CORS Headers: Configured for secure cross-origin resource sharing between the frontend and backend.

Deployment
Vercel: Optimized hosting for the frontend.

Production API: Backend endpoints configured for live environment access.

✨ Features
User Authentication: Secure login and signup modals.

Destination Discovery: Explore various travel spots with dynamic filtering.

Hotel Booking System: Real-time availability checks and booking management via dedicated APIs.

Responsive Design: Fully optimized for mobile, tablet, and desktop views.

Interactive UI: Smooth transitions and modern navigation elements.

📂 Project Structure
Plaintext
remo-travels/
├── src/                # React Frontend source files
├── travel_backend/     # Django Backend configuration & logic
├── public/             # Static assets
├── vercel.json         # Deployment configuration
├── vite.config.js      # Build tool configuration
└── tailwind.config.js  # Styling configuration

⚙️ Installation & Setup
1. Clone the repository
Bash
git clone https://github.com/Naveenkumar661/remo-travels.git
cd remo-travels
2. Frontend Setup
Bash
# Install dependencies
npm install

# Start the development server
npm run dev
3. Backend Setup
Bash
# Navigate to backend folder
cd travel_backend

# Install Python dependencies (ensure you have a virtualenv active)
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the server
python manage.py runserver
🛡️ Environment Variables
To run this project locally, ensure you configure your .env files for:

DATABASE_URL (MySQL Connection)

API_BASE_URL (Frontend pointer to Backend)

👨‍💻 Author
Naveen Kumar E

Full-Stack Developer

LinkedIn | GitHub
