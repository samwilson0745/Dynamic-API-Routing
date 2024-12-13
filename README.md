# Dynamic API Gateway

## FastAPI Setup
- Install dependencies: `pip install -r requirements.txt`
- Run locally: `uvicorn app.api.gateway:app --reload`

## Docker Commands
- Build FastAPI image: `cd app , docker build -t api-gateway .`
- Create an nginx.conf file inside the nginx folder
- Run the docker compose: `docker-compose up --build`

## Testing
- FastAPI Gateway: `http://localhost:8000`
- Nginx Proxy (FastAPI): `http://localhost:8080`
