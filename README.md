## Starting the app for development purposes
inpro-frontend-app requires inpro-backend-service to be up an running in order to do run the app locally.
Docker is used to start up the inpro-backend-service and mongodb.
This can be done in the following manner:

 - `docker logout`
 - `docker login` (then enter your username and password)
Navigate to the root directory of the project and run the following:
 - `docker-compose up -d` (this will start the relevant docker containers in a detached state)

This will get the containers up and running. You can run `docker ps` in order see the status of the containers

Now you can go ahead and start the app with `yarn start` and inpro-frontend-app should start and be available at http://localhost:3000

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
