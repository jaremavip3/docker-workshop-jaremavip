Used these commands to run frontend:
docker build -t frontend ./frontend
docker run -p 3000:3000 -e REACT_APP_BACKEND_URL=http://localhost:8000 frontend
