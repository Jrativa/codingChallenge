## Coding Challenge FactoredAI

### First way:
1. **Clone this repository**
2. **Run the command** `docker-compose up`

### Second way:
1. **Clone this repository**
2. **Go to backend directory**
3. **Run the command** `docker build -t coding_challenge_back .`
4. **Run the command** `docker run -d -p 8000:8000 --name backend_coding_challenge coding_challenge_back`
5. **Go to frontend directory**
6. **Run the command** `docker build -t coding_challenge_front .`
7. **Run the command** `docker run -d -p 5173:5173 --name frontend_coding_challenge coding_challenge_front`
