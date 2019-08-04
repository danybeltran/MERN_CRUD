Beginning
After cloning the repository, run the following command inside the root ( `./` ) directory, then insiside the `./backend/` directory :
```
npm install
```

After that installing the dependencies, make sure to first start the express server. On the terminal, from the root (`./`) directory, run the following command:

```
cd backend && nodemon server.js
```
(this is because we are using nodemon to watch for file changes in our `server.js` file inside the `./backend/` directory. Normally this is used only for development)


Then open a new terminal on the root ( `./` ) directory, and run the following command:

```
npm start
```

This will start the application that will be using the responses from the server. Though there isn't any `fetch()` method in any class Component, axios is being used.

You should now be able to see the app running on `http://localhost:3000`
