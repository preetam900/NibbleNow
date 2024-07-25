Add a .env file to the backend folder.
In .env file include below codes :
    
    MONGO_URI="mongodb://localhost:27017/foodmine-db"
    PORT = 5000
    JWT_SECRET=Sbj6pUD+0Vp9A4CqKcJl/tP2z3IYWk8MldD5JF2MQbY=NODE_ENV="development"

Open terminal :
  terminal 1: cd backend and run "npm i" then "npm run dev"
  terminal 2: cd frontend and run "npm i" then "npm start"

Make sure you don't have anything running on localhost:3000 and port: 5000
You can check and terminate the ports using the following commands:
      open cmd in your pc :
              run the following commands :
                    "netstat -ano | findstr :3000"
                      then copy the pid and then run the command by changing the pid :
                              "taskkill /PID <PID> /F"

