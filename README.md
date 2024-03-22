# Steps for Installation and running the project

Run the following command to clone the repository
```
git clone 
```
Go to ```frontend``` and ```backend``` directory to install packages
```
cd frontend
npm install
```
```
cd backend
npm install
```
# Configuration
Create ```.env``` file inside ```backend``` directory and copy the following code

```
MONGO_URI=Your mongodb URI
```

Create ```.env``` file inside ```frontend``` directory and copy the following code

```
REACT_APP_API_URL=http://localhost:5000/api/todos
```
# Run the App
Go to ```backend``` and ```frontend``` directory and start the server
```
cd backend
npm start
```
```
cd frontend
npm start
```

