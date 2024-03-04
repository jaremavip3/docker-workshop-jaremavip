Used next commands: 
docker build -t backend ./backend
docker run -p 8000:8000 -e PORT=8000 backend

## Running the backend

To run the backend, you need to have node installed locally. Next, you will need to install dependencies:

```
npm install
```

To run the app you should specify which port it will run on with th `PORT` environment variable. You can run the app with:
```
PORT=8000 node index.js
```
