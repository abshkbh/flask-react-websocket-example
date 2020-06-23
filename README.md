I struggled with a minimal example that bootstraps a WebSocket connection
between a React client and a Flask backend.

# Running the backend

# Only required for the first time
cd backend
python3 -m venv venv
. venv/bin/activate
pip3 install -r requirements.txt

# Run the server
./launch-server.sh

# Running the frontend
cd frontend
npm start
