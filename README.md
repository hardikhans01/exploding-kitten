# Exploding Kitten (Cat Card Game)

## Github link (https://github.com/hardikhans01/exploding-kitten)

## Description

This simple online single-player card game was built with React, Redux, Golang, and Redis. In this game, players draw cards from a randomly ordered deck and try to win by avoiding an exploding card.

Key Features ✨

1. Start Game: Users can start a new game with a randomly shuffled deck.
2. Draw and Shuffle: Players can draw a card or reshuffle the deck if they draw a Shuffle card.
3. Leaderboard: Tracks and displays players' scores. Each win counts as one point.
4. Username Selection: Players can enter a username before starting the game.
5. Backend API: The backend, written in Golang, manages user scores in Redis.

Technologies Used 🛠

1. Frontend: React, Redux (for state management)
2. Backend: Golang (for backend)
3. Database: Redis (to store user details and the scores)
4. Styling: TailwindCSS

## Running the Application Locally

Step-1. Clone the GitHub repo by running the git clone command.

```
git clone https://github.com/hardikhans01/exploding-kitten.git
```

Step-2

a. Install all the required packages and dependencies for frontend by running the below command in the client directory.

```
npm install
```

b. Install all the required packages and dependencies for backend by running the following command in the server directory.

```
go mod init server
```

```
go mod tidy
```

Step-3. export the following environment variables by running these commands in the command line.

```
export DATABASE=localhost:6379
export PORT=5000
```

Step-4. Start the frontend on your localhost by running the following command.

```
npm run dev
```

Step-5. Start the backend on your localhost by running the following command.

```
go run main.go
```

## Deployment

The application is deployed and is running live.

The frontend is deployed on Vercel.

Frontend Link - https://exploding-kitten-frontend-34qhma4gl-hardiks-projects-5759d44e.vercel.app/

The backend is deployed on render

Backend Link - https://exploding-kitten-backend-c951.onrender.com/
